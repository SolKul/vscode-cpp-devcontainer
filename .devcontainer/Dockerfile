FROM ubuntu:20.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get install -y git build-essential cmake clang libssl-dev && \
    apt-get install -y cpputest libsqlite3-dev clang-format gdb cmake-curses-gui
