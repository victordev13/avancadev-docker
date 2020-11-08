FROM golang:latest

WORKDIR /go/src/fullcycle/

COPY . .

RUN GOOS=linux go build c.go

EXPOSE 9092

ENTRYPOINT [ "./c" ]
