FROM node:18.15.0

WORKDIR /app

COPY . .

RUN apt-get -y update
RUN apt-get -y install -y --no-install-recommends git

ENTRYPOINT ["sleep", "infinity"]
