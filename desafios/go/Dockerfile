FROM golang:alpine

WORKDIR /app

COPY main.go /app/

RUN go mod init example.com/m && go mod tidy

RUN  go build -o app .

CMD ["./app"]