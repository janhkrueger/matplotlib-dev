FROM python:3.9-alpine
LABEL maintainer="janhkrueger@gmail.com"
RUN TZ=UTC

RUN apk update
RUN apk add g++ jpeg-dev zlib-dev libjpeg make git python3-dev openblas-dev gfortran build-base py3-pip linux-headers
RUN pip3 install numpy
RUN pip3 install matplotlib scipy
