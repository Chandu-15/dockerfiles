FROM nginx
RUN rm -rf /usr/share/nginx/html/
ONBUILD COPY  index.html /usr/share/nginx/html/
CMD ["sleep", "1000"]