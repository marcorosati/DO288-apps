# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent
EXPOSE 8080
RUN sed -i "s/Listen 80/Listen 8080/g" && \
    chgrp -R 0 /run/httpd
    chmod -R g=u /run/httd
USER 1001
