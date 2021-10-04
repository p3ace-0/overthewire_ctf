# Natas challenge writeup
&#8594; [link to the challenge](https://overthewire.org/wargames/natas/)
> *Let's hack the planet* 🔥\
-- P3ACE
---

#### Natas0 &#8594; Natas1 
    passwd: gtVrDuiDfck831PqWsLEZy5gyDz1clto
---

#### Natas1 &#8594; Natas2
    passwd: ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi
---

#### Natas2 &#8594; Natas3
    passwd: sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14
    info: flag found on http://natas2.natas.labs.overthewire.org/files/users.txt
---

#### Natas3 &#8594; Natas4
    passwd: Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ
    info: flag found on http://natas3.natas.labs.overthewire.org/s3cr3t/users.txt
---

#### Natas4 &#8594; Natas5
    passwd: iX6IOfmpN7AYOQGPwtn3fXpbaJVJcHfq
    info: change http request header referer option 
    doc: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Referer
---

### Natas5 &#8594; Natas6
    passwd: aGoY4q2Dc6MgDq4oL4YtoKtyAg9PeHa1
    info: change cookie loggedin to 1
    doc: https://en.wikipedia.org/wiki/HTTP_cookie
---

### Natas6 &#8594; Natas7
    passwd: 7z3hEENjQtflzgnT29q7wAvMNfZdh0i9
    info: check php included file
---

### Natas7 &#8594; Natas8
    passwd: DBfUBfqQG69KvJvJ1iAbMoIpwSNQ9bWe 
    info: Remote code execution
    doc: https://github.com/RoqueNight/LFI---RCE-Cheat-Sheet
