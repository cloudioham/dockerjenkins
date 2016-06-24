FROM debian:jessie
MAINTAINER HaTr
ENV REFRESHED_AT 2014-06-24
ENV http_proxy 'http://16.85.88.10:8088'
ENV https_proxy 'http://16.85.88.10:8088'
RUN apt-get update
RUN apt-get -y install ruby rake
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
