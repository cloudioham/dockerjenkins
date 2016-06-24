FROM centos:latest
MAINTAINER HaTr
ENV REFRESHED_AT 2016-06-24
ENV http_proxy 'http://16.85.88.10:8088'
ENV https_proxy 'http://16.85.88.10:8088'
RUN yum -y install ruby rubygems rubygem-rake
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
