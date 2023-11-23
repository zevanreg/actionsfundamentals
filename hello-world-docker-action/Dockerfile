FROM alpine:3.10

WORKDIR .
COPY entrypoint.sh .

RUN chmod +x entrypoint.sh
ENTRYPOINT ["/usr/src/entrypoint.sh"]
