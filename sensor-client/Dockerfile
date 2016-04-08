# Base image
FROM golang:1.4.2

# Maintainer info
MAINTAINER AirU <roylat.wilson@gmail.com>

# Get the project
RUN go get github.com/rolyatwilson/mars-challenge/sensor-client

# Set working directory
WORKDIR /go/src/github.com/rolyatwilson/mars-challenge/sensor-client

# Expose port
EXPOSE 8080

# Run Game Controller
CMD go run *.go
