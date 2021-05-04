FROM debian

RUN apt update -qq; apt install curl nginx -y; apt clean -y

COPY download-and-crop.sh /usr/local/bin/download-and-crop.sh

CMD /usr/local/bin/download-and-crop.sh
