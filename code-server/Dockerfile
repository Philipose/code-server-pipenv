FROM linuxserver/code-server:latest


RUN sudo apt update \
 && sudo apt install -y \
  python3.8 \
  python3.8-dev\
  python3-pip \
  libpq-dev \
  libxml2-dev \
  libxmlsec1-dev \
  libxmlsec1-openssl \
 && sudo rm -rf /var/lib/apt/lists/* \ 
 && pip3 install pipenv
