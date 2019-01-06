FROM ubuntu:16.04


RUN apt-get update && apt-get install -y \
curl
ADD curl.sh /
CMD ["/bin/bash", "/curl.sh"]
