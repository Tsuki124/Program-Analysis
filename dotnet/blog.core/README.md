前置基础
---

相关漏洞
---

### 文件读取
> https://github.com/anjoy8/Blog.Core/blob/master/Blog.Core.Api/Controllers/ImgController.cs

![image](https://user-images.githubusercontent.com/55024146/160284685-8ad48d54-d644-4e71-b892-e240d7f3b03e.png)

未对filename做任何处理，直接进行读取操作，可跨目录读取文件，如：
```
/images/Down/Bmd?filename=../appsettings.json
/images/Down/Bmd?filename=../WMBlog.db
```
### 文件上传
> https://github.com/anjoy8/Blog.Core/blob/master/Blog.Core.Api/Controllers/ImgController.cs

![image](https://user-images.githubusercontent.com/55024146/160284805-ebf42bcd-fc23-4a80-bed5-12d617d8690d.png)

这里只在76行处对请求包的ContentType进行了白名单校检，而82行拼接文件写入的目标路径部分，使用的是file.FileName，可控。


参考资料:
```
https://www.x1a0t.com/2021/01/20/Blog-Core-Arbitrary-File-Read-and-Upload/
```
