# Creates an Ambari Server base on vanilla centos
FROM sequenceiq/ambari:1.7.0-consul
MAINTAINER SequenceIQ


COPY start-agent /start-agent
COPY start-server /start-server

EXPOSE 8080
CMD ["/start-server"]
