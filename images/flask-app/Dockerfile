FROM alpine:3.9

COPY assets/ /tmp/assets/

RUN echo '[INFO] Configure environment' && \
    /tmp/assets/sbin/install.sh 

WORKDIR /app        
ENTRYPOINT ["/sbin/entrypoint.sh"]
