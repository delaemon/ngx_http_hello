# ngx_http_hello
```
$ git clone git@github.com:delaemon/ngx_http_hello.git
$ cd nginx
$ ./auto/configure \
--prefix=/usr/local/nginx \
--with-openssl=/usr/lib64/openssl \
--add-module=../ngx_http_hello
$ make
$ sudo make install
$ sudo /usr/local/nginx/sbin/nginx
$ sudo /usr/local/nginx/sbin/nginx -s reload
$ sudo /usr/local/nginx/sbin/nginx -s stop
```
