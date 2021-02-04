FROM golang:1.15

WORKDIR /go/src/pix
COPY . .
RUN GOOS=linux go build
CMD ["./pix"]