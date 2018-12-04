FROM golang:1.10
RUN apt-get update -qq

WORKDIR /go/src/app

ADD ./application /go/src/app
RUN go build
