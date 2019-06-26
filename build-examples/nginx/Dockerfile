#
# docker build -t image .
# docker run -d -p80:80 image
# docker exec 79ed6c85e331 sh -c "echo changed page > /usr/share/nginx/html/index.html"
# curl localhost
#
FROM nginx
LABEL maintainer="theprotos"
RUN echo "default page" > /usr/share/nginx/html/index.html
VOLUME /usr/share/nginx/html/
