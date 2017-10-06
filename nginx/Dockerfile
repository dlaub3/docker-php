FROM nginx:latest
RUN  rm -R /etc/nginx/conf.d/
ADD ../../app /code
ADD ../site.conf:/etc/nginx/conf.d/site.conf
