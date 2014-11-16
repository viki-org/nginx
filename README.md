To package Nginx, clone this repo, clean it add psol...
```
find debian/ -name '\.git*' -exec rm -rf {} \; &>/dev/null
rm -r debian/modules/nginx-upload-progress/test/
rm -r debian/modules/nginx-rtmp-module/test/
rm README.md
cd debian/modules/ngx_pagespeed && wget http://dl.google.com/dl/page-speed/psol/1.9.32.2.tar.gz
```
... and build it your favorite way
