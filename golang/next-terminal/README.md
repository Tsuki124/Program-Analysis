相关漏洞
---

### 权限绕过
项目地址
- https://github.com/dushixiang/next-terminal/tree/v0.2.7

漏洞位置
> https://github.com/dushixiang/next-terminal/blob/v0.2.7/pkg/api/middleware.go

![image](https://user-images.githubusercontent.com/55024146/155908129-9c86b76a-5f9f-48bc-8f63-e8af1a63be6a.png)

路由中如果携带了urls中的关键字，则放行.

☞ 与java中的鉴权问题有着异曲同工之妙:

```java
# 如果包含 *.html则直接放行（使用的是 contains 方法，只要url包含这些字符串即可通过权限校验）
if (requestUrl != null && (requestUrl.contains("/doc.html") || 
    requestUrl.contains("/register.html") || requestUrl.contains("/login.html"))) {
    chain.doFilter(request, response);
    return;
}
```

ref
- https://xiaokou.top/article?key=qVRi44
