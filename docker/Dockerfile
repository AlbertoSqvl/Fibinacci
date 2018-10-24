FROM golang:latest
MAINTAINER Sergio Alberto <alberto.camarena@g-tec.io>
RUN mkdir /app
ADD . /app/
WORKDIR /app
RUN go build -o fibon_ws .
EXPOSE 8080
CMD ["/app/fibon_ws"]
