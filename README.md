# nginx-mac-rtmp-enabled
Rtmp enabled pre build Nginx with fix

CFLAGS+="-Wno-unused-but-set-variable" ./configure \                                                                                                                          ✔  11s  system   08:02:07 PM
  --prefix=/opt/homebrew/Cellar/nginx-full/1.27.0 \
  --add-module=nginx-rtmp-module \
  --with-http_ssl_module \
  --with-pcre \
  --with-ipv6 \
  --sbin-path=/opt/homebrew/Cellar/nginx-full/1.27.0/bin/nginx \
  --with-cc-opt='-I/opt/homebrew/include -I/opt/homebrew/opt/pcre/include -I/opt/homebrew/opt/openssl@3/include' \
  --with-ld-opt='-L/opt/homebrew/lib -L/opt/homebrew/opt/pcre/lib -L/opt/homebrew/opt/openssl@3/lib' \
  --conf-path=/opt/homebrew/etc/nginx/nginx.conf \
  --pid-path=/opt/homebrew/var/run/nginx.pid \
  --lock-path=/opt/homebrew/var/run/nginx.lock \
  --http-client-body-temp-path=/opt/homebrew/var/run/nginx/client_body_temp \
  --http-proxy-temp-path=/opt/homebrew/var/run/nginx/proxy_temp \
  --http-fastcgi-temp-path=/opt/homebrew/var/run/nginx/fastcgi_temp \
  --http-uwsgi-temp-path=/opt/homebrew/var/run/nginx/uwsgi_temp \
  --http-scgi-temp-path=/opt/homebrew/var/run/nginx/scgi_temp \
  --http-log-path=/opt/homebrew/var/log/nginx/access.log \
  --error-log-path=/opt/homebrew/var/log/nginx/error.log

