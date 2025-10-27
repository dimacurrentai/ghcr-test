FROM alpine:latest
RUN echo one
RUN sleep 10
RUN echo two
RUN sleep 10
RUN echo three
ENTRYPOINT ["/bin/sh", "-c", "echo 'Yo inner GHCR!'"]
