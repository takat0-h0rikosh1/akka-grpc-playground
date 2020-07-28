# Akka gRPC Play Ground

### 動かし方

#### サーバー起動

```sh
sbt "runMain example.helloworld.GreeterServer"
```

#### クライアントからリクエスト

```sh
sbt "runMain example.helloworld.GreeterClient"
```

### メモ

jdk の version が 8u252 以降でないと正しく動作しない可能性があります。
