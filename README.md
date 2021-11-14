# Tor-Magic
```

▄▄▄▄▄      ▄▄▄  • ▌ ▄ ·.  ▄▄▄·  ▄▄ • ▪   ▄▄· 
•██  ▪     ▀▄ █··██ ▐███▪▐█ ▀█ ▐█ ▀ ▪██ ▐█ ▌▪
 ▐█.▪ ▄█▀▄ ▐▀▀▄ ▐█ ▌▐▌▐█·▄█▀▀█ ▄█ ▀█▄▐█·██ ▄▄
 ▐█▌·▐█▌.▐▌▐█•█▌██ ██▌▐█▌▐█ ▪▐▌▐█▄▪▐█▐█▌▐███▌
 ▀▀▀  ▀█▄▀▪.▀  ▀▀▀  █▪▀▀▀ ▀  ▀ ·▀▀▀▀ ▀▀▀·▀▀▀ 

         *         .  _.---._          .      
               *    .'       '.  .            
                _.-~===========~-._ *         
             .  (___________________)       *  
             *       \_______/        .       
            T0R-Magic....                                      

Public Internet Address came back with ~>  107.189.7.243
[*] Sent GET Request using ->  socks5://127.0.0.1:9050


```
simple and easy to use HTTP analyzation<br>
<br>
Simple HTTP analyzation written from pure golang, wanted to grab simple info from a http request header but stay hidden? well using this tool you can, this tool is fast, reliable, open source, easy to use and install ( part of the recent toolkit)
<br>
<br>
# syntax 

```
go run main.go -h or -t <url>
NOTE: MAKE SURE YOU HAVE TOR INSTALLED AND CONFIGURED

INSTALLS

|-> git clone https://github.com/ArkAngeL43/Tor-Magic.git ; go get github.com/PuerkitoBio/goquery ; go get golang.org/x/net/proxy


```

 

# what wil it get 

```
BASICS

Public Internet Address came back with ~>  45.61.185.53
[*] Sent GET Request using ->  socks5://127.0.0.1:9050
--------------------------Server Response---------------------------
[+] Response Status  ->  200 OK
[+] Date Of Request  ->  Sun, 14 Nov 2021 08:35:15 GMT
[+] Content-Encoding ->  
[+] Content-Type     ->  text/html; charset=utf-8
[+] Connected-Server ->  GitHub.com
[+] X-Frame-Options  ->  deny
--------------------------Server X-Requests-----------------------------
-------------------------- URL PARSED -------------- 
Scheme        --->  https
Hostname      --->  github.com
Path in URL   --->  /ArkAngeL43/Tor-Magic/edit/main/README.md
Query Strings --->  
Fragments     --->  
-------------- URL QUERY VALS ----------------------- 

```

```
ADVANCED: Will attempt to grab URL Query VALS

[+] -> Set-Cookie -> [_device_id=c8c1ee0ded98a65c1f0aed9d5d3c3d10; path=/; expires=Mon, 14 Nov 2022 08:35:15 GMT; secure; HttpOnly; SameSite=Lax _octo=GH1.1.1204477415.1636878915; domain=.github.com; path=/; expires=Mon, 14 Nov 2022 08:35:15 GMT; secure; SameSite=Lax logged_in=no; domain=.github.com; path=/; expires=Mon, 14 Nov 2022 08:35:15 GMT; secure; HttpOnly; SameSite=Lax _gh_sess=MGOxr36X%2FBc6s6hzXZh1abXRsYMkRDTwrO6gi9xf%2Fnmka2pIfT%2BS%2Fi9pzCCBwSLNkRkVxbUcOo7Zk4nRMggF0UCcHwnr7S%2FDRUDqiid26zbA2UF3fPC%2B7mqiKQUbXcg76%2B%2FCM7ybstqZsx4evgCZmzFG0he6SYD2t3bAPmC831XQpbsRqeIU7yrcsmpH%2BsrgeFXtjA0FAlnCcB1h%2FKrmtcLkK1avcLJffpE1VuULrGsDBtUa%2FX1G7vECQM2ErC1jr3nPgOxRlitIFYODtmMang%3D%3D--d2kG%2B85x6uWsUKDN--hrDSuqN%2F0USeZAEt0W8Rig%3D%3D; path=/; secure; HttpOnly; SameSite=Lax]
[+] -> X-Frame-Options -> [deny]
[+] -> Referrer-Policy -> [origin-when-cross-origin, strict-origin-when-cross-origin]
[+] -> Expect-Ct -> [max-age=2592000, report-uri="https://api.github.com/_private/browser/errors"]
[+] -> Content-Type -> [text/html; charset=utf-8]
[+] -> Vary -> [X-PJAX, X-PJAX-Container Accept-Encoding, Accept, X-Requested-With]
[+] -> Cache-Control -> [no-store]
[+] -> Content-Security-Policy -> [default-src 'none'; base-uri 'self'; block-all-mixed-content; child-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/; connect-src 'self' uploads.github.com objects-origin.githubusercontent.com www.githubstatus.com collector.githubapp.com api.github.com github-cloud.s3.amazonaws.com github-production-repository-file-5c1aeb.s3.amazonaws.com github-production-upload-manifest-file-7fdce7.s3.amazonaws.com github-production-user-asset-6210df.s3.amazonaws.com cdn.optimizely.com logx.optimizely.com/v1/events translator.github.com wss://alive.github.com; font-src github.githubassets.com; form-action 'self' github.com gist.github.com objects-origin.githubusercontent.com; frame-ancestors 'none'; frame-src render.githubusercontent.com viewscreen.githubusercontent.com notebooks.githubusercontent.com; img-src 'self' data: github.githubassets.com identicons.github.com collector.githubapp.com github-cloud.s3.amazonaws.com secured-user-images.githubusercontent.com/ *.githubusercontent.com; manifest-src 'self'; media-src github.com user-images.githubusercontent.com/; script-src github.githubassets.com; style-src 'unsafe-inline' github.githubassets.com; worker-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/]
[+] -> X-Github-Request-Id -> [CF5E:14A4:1B7940D:2E11894:6190CA43]
[+] -> Permissions-Policy -> [interest-cohort=()]
[+] -> Etag -> [W/"3a42c2b05c663035b7545a1260ade199"]
[+] -> X-Content-Type-Options -> [nosniff]
[+] -> X-Xss-Protection -> [0]
[+] -> Server -> [GitHub.com]
[+] -> Date -> [Sun, 14 Nov 2021 08:35:15 GMT]
[+] -> Strict-Transport-Security -> [max-age=31536000; includeSubdomains; preload]

```

```
ALL: HREF and CODE notes 
#start-of-content
https://docs.github.com/articles/supported-browsers
https://github.com/
/password_reset
/signup?return_to=https%3A%2F%2Fgithub.com%2FArkAngeL43%2FTor-Magic%2Fedit%2Fmain%2FREADME.md&source=login
/site/terms
/site/privacy
https://docs.github.com/articles/github-security/
https://github.com/contact


----------------------------- GATHERING CODE NOTES ----------------------
[`] Completed at ->  2021-11-13 22:35:19.278969335 -0500 EST m=+6.873274148
<!-- '"` -->
[`] Completed at ->  2021-11-13 22:35:19.279157849 -0500 EST m=+6.873462642
<!-- </textarea></xmp> -->


```
