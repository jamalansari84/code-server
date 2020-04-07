FROM node:12

ENV GOPATH=/go
ENV GOBIN=/go/bin
RUN echo "export PATH=$PATH:$GOBIN" >> /.bashrc

RUN apt-get update && apt-get install -y \
    curl \
    iproute2 \
    vim \
    iptables \
    net-tools \
    libsecret-1-dev \
    libx11-dev \
    libxkbfile-dev

CMD ["/bin/bash"]
