FROM node:6.10

RUN apt-get update -y
RUN apt-get install -y \
    apt-utils \
    ssh \
    gcc \
    make \
    curl \
    man \
    git \
    less \
    python-software-properties \
    software-properties-common \
    wget \
    dos2unix \
    apt-transport-https \
    lsb-release \
    ca-certificates \
    rsync \
    build-essential

RUN npm install -g express-generator
RUN mkdir -p /home/nodeapp
WORKDIR /home/nodeapp
CMD ["/bin/bash"]
