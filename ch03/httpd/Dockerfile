# CoreOS Base
FROM fedora:latest
# Install httpd
RUN echo "Installing httpd"; yum -y install httpd
COPY index.html /var/www/html/index.html
# Expose the default httpd port 80
EXPOSE 80
# Run httpd
CMD ["/usr/sbin/httpd", "-DFOREGROUND"]
