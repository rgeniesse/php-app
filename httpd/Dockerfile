FROM httpd:2.4-alpine

COPY conf/custom.conf /usr/local/apache2/conf/custom.conf

RUN printf "Include conf/custom.conf\n" >> /usr/local/apache2/conf/httpd.conf