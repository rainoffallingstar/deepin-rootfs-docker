# Dockerfile
FROM scratch
ADD deepin-rootfs.tar /

# Install software
RUN apt-get update && apt-get upgrade -y  \
    && rm -rf /var/lib/apt/lists/* 

RUN rm -rf /tmp/download_packages

# Define default command.

EXPOSE 80
EXPOSE 8787

CMD ["/usr/sbin/init"]
