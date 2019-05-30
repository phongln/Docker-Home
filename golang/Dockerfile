FROM golang:latest

ENV APP_ROOT /src

WORKDIR $APP_ROOT

RUN apt-get update && apt-get upgrade -y

COPY . $APP_ROOT
RUN chmod +x $APP_ROOT

CMD ["/bin/sleep", "100000000"]