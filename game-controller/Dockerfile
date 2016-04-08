# Base image
FROM golang:1.4.2

# Maintainer info
MAINTAINER AirU <rolyat.wilson@gmail.com>

# Get the project
RUN go get github.com/rolyatwilson/mars-challenge/game-controller

# Set working directory
WORKDIR /go/src/github.com/rolyatwilson/mars-challenge/game-controller

# Expose port
EXPOSE 8080

# Run Game Controller
CMD go run *.go
