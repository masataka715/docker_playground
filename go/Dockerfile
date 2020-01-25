FROM golang:latest

# コンテナ内に作業ディレクトリを作成
RUN mkdir /go/src/work

# コンテナログイン時のディレクトリ指定
WORKDIR /go/src/work

ADD ./src /go/src/work

# 8080 ポートを解放
EXPOSE 8080