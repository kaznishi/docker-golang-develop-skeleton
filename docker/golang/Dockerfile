FROM golang:1-stretch

RUN go get -v github.com/tockins/realize \
    && go get -v github.com/golang/dep/cmd/dep

COPY . /go/src/kaznishi/docker-golang-develop-skeleton
WORKDIR /go/src/kaznishi/docker-golang-develop-skeleton

CMD [ "realize", "start"]