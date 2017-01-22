# fukuitech 06 Docker demo
## How to
### Gitが入っている場合
```shell
$ git clone git@github.com:unasuke/fukuitech-06-demo.git
$ cd fukuitech-06-demo
```

### Gitが入っていない場合
右上の緑の「Clone or download」から、「Download ZIP」をクリックしてダウンロードしたzipファイルの中で作業します。

### 実行
```shell
$ docker run -p 3000:3000 unasuke/fukuitech-06-demo
```

### docker imageのビルド
```shell
$ docker build -t fukuitech-06-demo .
```

### ビルドしたイメージの実行
```shell
$ docker run -p 3000:3000 fukuitech-06-demo
```

## 外部リンク
- [unasuke/fukuitech-06](https://github.com/unasuke/fukuitech-06)
- [https://hub.docker.com/r/unasuke/fukuitech-06-demo/](https://hub.docker.com/r/unasuke/fukuitech-06-demo/)
- [https://hub.docker.com/r/unasuke/h2o-alpine/](https://hub.docker.com/r/unasuke/h2o-alpine/)
- [h2o-alpine(gist)](https://gist.github.com/unasuke/01d78fdd67658de22c2b91e00ba5e0d6)
