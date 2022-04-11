FROM ubuntu:18.04

# install tools.
RUN apt update && \
    apt install -y net-tools iputils-ping curl

ENTRYPOINT ["/bin/sh", "-c", "/usr/bin/tail -f /dev/null"]
