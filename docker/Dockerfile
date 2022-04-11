FROM golang:1.15-alpine

ENV CGO_ENABLED=0

ADD ./server /app/

WORKDIR /app/

CMD [ "./server" ]