FROM ubuntu:16.04

# Install prerequisites
RUN apt-get update
RUN apt-get install -y curl python 

RUN curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl 

RUN chmod a+x /usr/local/bin/youtube-dl 

EXPOSE 4567
ENV LC_ALL=C.UTF-8 

ENTRYPOINT ["/usr/local/bin/youtube-dl"]
