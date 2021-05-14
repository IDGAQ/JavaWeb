# Cookie
---

```java
// 创建Cookie (Servlet)
Cookie newCookie = new Cookie(String key, Object value);

//写入Cookie (Servlet)
response.addCookie(newCookie);

//读取Cookie (JSP)
Cookie[] cookies = request.getCookies();
```
