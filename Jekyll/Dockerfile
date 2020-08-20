FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install ruby-full build-essential zlib1g-dev -y
RUN gem install bundler jekyll
EXPOSE 4000/tcp