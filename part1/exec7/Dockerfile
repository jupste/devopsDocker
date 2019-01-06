FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
curl
ADD /app /
RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
EXPOSE 8000
EXPOSE 5000
RUN npm install
CMD ["/bin/bash"]
