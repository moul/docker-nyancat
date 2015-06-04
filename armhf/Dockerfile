FROM armbuild/ubuntu:14.04
MAINTAINER Manfred Touron <m@42.am> (@moul)

ADD qemu-arm-static /usr/local/bin/

RUN apt-get update \
 && apt-get -y -q install nyancat \
 && apt-get clean

CMD ["/usr/bin/nyancat"]
