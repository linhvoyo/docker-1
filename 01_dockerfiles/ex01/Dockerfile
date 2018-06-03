
FROM debian

RUN apt-get update && apt-get install -y wget bzip2

WORKDIR /root
RUN wget http://dl.4players.de/ts/releases/3.0.13.8/teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2
RUN tar xfvj teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2

EXPOSE 9987/udp 
EXPOSE 30033
EXPOSE 10011
