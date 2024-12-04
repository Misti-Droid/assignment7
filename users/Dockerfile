FROM alpine

RUN mkdir /structure && chmod 777 /structure

RUN adduser -D -u 5000 collin

USER sync
WORKDIR /structure
CMD touch sync-work 

USER nobody
WORKDIR /structure
CMD touch nobody-work