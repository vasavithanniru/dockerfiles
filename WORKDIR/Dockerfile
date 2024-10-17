FROM almalinux:9
RUN useradd expense
USER expense
RUN mkdir /tmp/docker
WORKDIR /tmp/docker
RUN pwd
RUN echo "HELLO" > hello.txt
CMD ["sleep", "100"]