FROM ubuntu:16.04
RUN apt-get update -y
RUN apt-get -y install fortune
COPY fourtunescript.sh /bin/fourtunescript.sh
RUN chmod 777 /bin/fourtunescript.sh
ENTRYPOINT ["bash","fourtunescript.sh"]

