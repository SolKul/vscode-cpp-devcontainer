FROM ubuntu:20.04
ARG DEBIAN_FRONTEND=noninteractive
# 日本経由でダウンロード
RUN sed -i.org -e 's|archive.ubuntu.com|jp.archive.ubuntu.com|g' /etc/apt/sources.list
RUN apt update && \
    apt install -y git build-essential cmake clang libssl-dev && \
    apt install -y cpputest libsqlite3-dev clang-format gdb cmake-curses-gui
