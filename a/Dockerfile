FROM golang:latest

WORKDIR /go/src/fullcycle/

COPY . .

RUN GOOS=linux go build a.go

EXPOSE 9090

ENTRYPOINT [ "./a" ]
