FROM nginx:1.19-alpine

# settings
COPY .docker/nginx/conf/default.conf /usr/local/etc/nginx/conf.d/default.conf
# 絶対パスで書くほうがいい
VOLUME /app
