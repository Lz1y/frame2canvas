# frame2canvas
## 当某些资源被做了referer限制时，无法直接请求得到正确返回内容。  
插入xss payload，用iframe包含同源页面，读取iframe的document.body，使用html2canvas截图并以post传输到攻击者服务端。
