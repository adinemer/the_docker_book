FROM centos:latest
LABEL maintainer="adi.nemer@gmail.com"
ENV REFRESHED_AT 2023-03-05
RUN yum -y install ruby rubygems rubygem-rake
RUN gem install --no-document rspec ci_reporter_rspec
