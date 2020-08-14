FROM ubuntu:20.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt update && \
    apt install -y git build-essential cmake clang libssl-dev && \
    apt install -y cpputest libsqlite3-dev clang-format gdb cmake-curses-gui
