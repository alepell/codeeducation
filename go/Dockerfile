FROM golang:1.14 AS builder

WORKDIR /go/src/app

RUN touch fullcycle.go

RUN echo 'package main\n import "fmt"\n func main() {fmt.Println("Code.education Rocks!")}' >> fullcycle.go

RUN go build fullcycle.go

ENTRYPOINT [ "./fullcycle"]
