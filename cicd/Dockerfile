FROM python:2.7-alpine as dependencies

RUN apk add --no-cache \
    nodejs npm 

ENV PATH $PATH:/usr/local/bin/
ENV PYTHON /usr/local/bin/