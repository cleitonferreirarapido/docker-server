FROM	nginx:1.19.5-alpine
LABEL 	maintainer "rodrigo@uware.com.br"

RUN	apk update && apk add --no-cache certbot certbot-nginx && mkdir -p /srv/http
EXPOSE	80 443
