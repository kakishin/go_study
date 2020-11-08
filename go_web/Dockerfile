# ベースとなるDockerイメージ指定
FROM golang:alpine3.12
# コンテナ内に作業ディレクトリを作成
RUN mkdir -p /go/src
# コンテナログイン時のディレクトリ指定
WORKDIR /go/src
# ホストのファイルをコンテナの作業ディレクトリに移行
ADD ./src/ /go/src