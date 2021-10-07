FROM debian:stable-slim

WORKDIR /
ADD . /

RUN mkdir -p /machine && chmod +x /filestat_exporter

ENTRYPOINT ["/filestat_exporter", "-config.file", "/filestat.yaml"]
