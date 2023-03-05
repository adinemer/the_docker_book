FROM  ubuntu:22.04
LABEL maintainer="adi.nemer@gmail.com"
ENV REFRESHED_AT 2023-03-05
RUN apt update
RUN apt -y install ruby rake
RUN gem install --no-document rspec ci_reporter_rspec
