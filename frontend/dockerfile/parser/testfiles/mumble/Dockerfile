FROM ubuntu:14.04@sha256:d7a459ecd77ebb09525584f2c3e1bb7f6a2879d90df8a3523c1b899dfc2a226f

RUN apt-get update && apt-get install libcap2-bin mumble-server -y

ADD ./mumble-server.ini /etc/mumble-server.ini

CMD /usr/sbin/murmurd
