FROM nginx

RUN apt update -qq; apt install curl unzip -y; apt clean -y

COPY 90-download-and-crop.sh /docker-entrypoint.d/
