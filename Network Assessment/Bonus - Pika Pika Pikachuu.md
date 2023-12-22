On using strings with the pcap file

```
┌──(kali㉿kali)-[~/Desktop]
└─$ strings pcaptest.pcapng 
Apple M2
macOS 14.1.2, build 23B92 (Darwin 23.1.0)
Dumpcap (Wireshark) 4.2.0 (v4.2.0-0-g54eedfc63953)
macOS 14.1.2, build 23B92 (Darwin 23.1.0)
POST http://127.0.0.1/login.php HTTP/1.1
Host: 127.0.0.1
Proxy-Connection: keep-alive
Content-Length: 31
Cache-Control: max-age=0
sec-ch-ua: "Not_A Brand";v="8", "Chromium";v="120"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "macOS"
Upgrade-Insecure-Requests: 1
Origin: http://127.0.0.1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.6099.71 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: http://127.0.0.1/
Accept-Encoding: gzip, deflate, br, zstd
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
username=user&password=password
POST /login.php HTTP/1.1
Host: 127.0.0.1
Content-Length: 31
Cache-Control: max-age=0
sec-ch-ua: "Not_A Brand";v="8", "Chromium";v="120"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "macOS"
Upgrade-Insecure-Requests: 1
Origin: http://127.0.0.1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.6099.71 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: http://127.0.0.1/
Accept-Encoding: gzip, deflate, br
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
Connection: close
username=user&password=password
#2HTTP/1.1 200 OK
Date: Fri, 22 Dec 2023 09:00:30 GMT
Server: Apache/2.4.54 (Debian)
X-Powered-By: PHP/7.4.33
Content-Length: 17
Connection: close
Content-Type: text/html; charset=UTF-8
Login successful!
-wHTTP/1.1 200 OK
Date: Fri, 22 Dec 2023 09:00:30 GMT
Server: Apache/2.4.54 (Debian)
X-Powered-By: PHP/7.4.33
Content-Length: 17
Connection: close
Content-Type: text/html; charset=UTF-8
Login successful!
Oo4+
K?WL
7>HX
~       J 
)aG;X
rDV=
;Q.7U
ZXF@
HwFV
JHm,
&Up6
POST http://127.0.0.1/login.php HTTP/1.1
Host: 127.0.0.1
Proxy-Connection: keep-alive
Content-Length: 47
Cache-Control: max-age=0
sec-ch-ua: "Not_A Brand";v="8", "Chromium";v="120"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "macOS"
Upgrade-Insecure-Requests: 1
Origin: http://127.0.0.1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.6099.71 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: http://127.0.0.1/
Accept-Encoding: gzip, deflate, br, zstd
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
username=user&password=KPMG_CTF%7B34c60d4cba2c8
POST /login.php HTTP/1.1
Host: 127.0.0.1
Content-Length: 47
Cache-Control: max-age=0
sec-ch-ua: "Not_A Brand";v="8", "Chromium";v="120"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "macOS"
Upgrade-Insecure-Requests: 1
Origin: http://127.0.0.1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.6099.71 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: http://127.0.0.1/
Accept-Encoding: gzip, deflate, br
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
Connection: close
username=user&password=KPMG_CTF%7B34c60d4cba2c8
8HTTP/1.1 200 OK
Date: Fri, 22 Dec 2023 09:00:57 GMT
Server: Apache/2.4.54 (Debian)
X-Powered-By: PHP/7.4.33
Content-Length: 29
Connection: close
Content-Type: text/html; charset=UTF-8
Invalid username or password.
4 Qt8
O Qt8
!Qt8
!Qt8
HTTP/1.1 200 OK
Date: Fri, 22 Dec 2023 09:00:57 GMT
Server: Apache/2.4.54 (Debian)
X-Powered-By: PHP/7.4.33
Content-Length: 29
Connection: close
Content-Type: text/html; charset=UTF-8
Invalid username or password.
bQt8
bQt8
VeW@C
#bQt8
VeW@C
eQt8
VeW@C
eQt8
G%WnJ
)kK1v
PP_E
me[N
3r@7
E5vO
POST http://127.0.0.1/login.php HTTP/1.1
Host: 127.0.0.1
Proxy-Connection: keep-alive
Content-Length: 31
Cache-Control: max-age=0
sec-ch-ua: "Not_A Brand";v="8", "Chromium";v="120"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "macOS"
Upgrade-Insecure-Requests: 1
Origin: http://127.0.0.1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.6099.71 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: http://127.0.0.1/
Accept-Encoding: gzip, deflate, br, zstd
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
username=user&password=password
~       J 
)aG;X
mAPOST /login.php HTTP/1.1
Host: 127.0.0.1
Content-Length: 31
Cache-Control: max-age=0
sec-ch-ua: "Not_A Brand";v="8", "Chromium";v="120"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "macOS"
part-flag : "a9894076d16e49db665}"
Upgrade-Insecure-Requests: 1
Origin: http://127.0.0.1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.6099.71 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: http://127.0.0.1/
Accept-Encoding: gzip, deflate, br
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
Connection: close
username=user&password=password
HTTP/1.1 400 Bad Request
Date: Fri, 22 Dec 2023 09:01:24 GMT
Server: Apache/2.4.54 (Debian)
Content-Length: 302
Connection: close
Content-Type: text/html; charset=iso-8859-1
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>400 Bad Request</title>
</head><body>
<h1>Bad Request</h1>
<p>Your browser sent a request that this server could not understand.<br />
</p>
<hr>
<address>Apache/2.4.54 (Debian) Server at 172.17.0.2 Port 80</address>
</body></html>
HTTP/1.1 400 Bad Request
Date: Fri, 22 Dec 2023 09:01:24 GMT
Server: Apache/2.4.54 (Debian)
Content-Length: 302
Connection: close
Content-Type: text/html; charset=iso-8859-1
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>400 Bad Request</title>
</head><body>
<h1>Bad Request</h1>
<p>Your browser sent a request that this server could not understand.<br />
</p>
<hr>
<address>Apache/2.4.54 (Debian) Server at 172.17.0.2 Port 80</address>
</body></html>
Counters provided by dumpcap
5NIv

```

I found `KPMG_CTF{34c60d4cba2c8` in the first part of the file and `a9894076d16e49db665}` in the `part-flag` header.

```
KPMG_CTF{34c60d4cba2c8a9894076d16e49db665}
```