FROM httpd:2.4
RUN cd conf && sed -i 's/Listen 80/Listen 9999/g' httpd.conf
COPY index.html /usr/local/apache2/htdocs/ 
EXPOSE 9999
CMD [ "echo","CONTAINER" ]