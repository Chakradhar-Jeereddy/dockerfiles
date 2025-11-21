FROM almalinux:9
RUN dnf install nginx -y
RUN useradd chakra
RUN mkdir /tmp/chakra
WORKDIR /tmp/chakra
CMD [ "sleep", "500" ]
USER chakra