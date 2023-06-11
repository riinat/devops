FROM golang:1.16

EXPOSE 8080

WORKDIR /app

COPY . /app

EXPOSE 8080

RUN go build

CMD ["./server"]