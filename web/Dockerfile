FROM golang:1.15.6-alpine3.12

WORKDIR /static

COPY . .

RUN go build dispatcher.go

CMD ["./dispatcher"]

EXPOSE 80