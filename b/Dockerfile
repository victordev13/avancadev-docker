FROM golang:latest

WORKDIR /go/src/fullcycle/

COPY . .

RUN GOOS=linux go build b.go

ENTRYPOINT [ "./b" ]
