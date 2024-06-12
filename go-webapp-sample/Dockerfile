FROM golang:alpine3.20 AS builder

WORKDIR /usr/src/app
COPY go.mod go.sum ./
RUN go mod download

COPY . .

RUN go build -o myapp .

FROM alpine:3.17

WORKDIR /root/

COPY --from=builder /usr/src/app/myapp .

EXPOSE 8080

CMD ["./myapp"]
