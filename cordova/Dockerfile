FROM android/node

ENV CORDOVA_VERSION 6.4.0

WORKDIR "/tmp"

RUN npm i -g --unsafe-perm cordova@${CORDOVA_VERSION}

ENV CI "yes"

RUN mkdir -p /src
WORKDIR /src