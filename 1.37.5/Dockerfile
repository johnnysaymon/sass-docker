FROM ubuntu:20.04

RUN apt-get update
RUN apt-get install -y wget
RUN mkdir extract
RUN wget -O extract/dart-sass.tar.gz https://github.com/sass/dart-sass/releases/download/1.37.5/dart-sass-1.37.5-linux-x64.tar.gz
RUN tar -C extract -zxf extract/dart-sass.tar.gz
RUN mv extract/dart-sass/sass /usr/local/bin/
RUN rm -r extract
