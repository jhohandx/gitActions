FROM nginx:alpine
RUN rm -rf /usr/share/nginx/html/index.*
COPY . /usr/share/nginx/html
COPY nginx.conf /etc/nginx
