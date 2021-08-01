# redoc

```
image for execution of redoc-cli
```

* [ReDoc-CLI](https://github.com/Redocly/redoc/blob/master/cli/README.md)


## Usage
```shell
docker build -t redoc-cli:1.0.0 .
docker run --rm -it -v${PWD}:/tmp redoc-cli:1.0.0 bash
```

Containerの中で以下コマンドを実施。
```shell
cd /tmp
redoc-cli bundle openapi.yaml
```
これで、HTMLファイルが出力される。

```shell
exit
```
