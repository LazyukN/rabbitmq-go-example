FROM golang:latest

ENV APP_NAME main.go

COPY . /go/src/${APP_NAME}
WORKDIR /go/src/${APP_NAME}

RUN go get ./
RUN go build main.go

CMD ./main