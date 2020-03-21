FROM golang:1.14

WORKDIR /go/src

COPY . .

RUN GOOS=linux go build hello.go

EXPOSE 8081

ENTRYPOINT [ "./hello" ]