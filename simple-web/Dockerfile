FROM golang:1.10

WORKDIR /build

COPY . .

RUN go build -o app server.go

# This container exposes port 8080 to the outside world
EXPOSE 8080

# Run the executable
CMD ["./app"]