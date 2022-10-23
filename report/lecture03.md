## 第3回


> AP サーバーの名前とバージョンを確認してみましょう。

```
* Puma version: 5.6.4 (ruby 2.6.3-p62) ("Birdie's Version")
```

> AP サーバーを終了させた場合、引き続きアクセスできますか？結果を確認して、また AP サー
バーを起動してください。

- Oopsにてアクセスできなくなった。
- APサーバーを起動するとまたアクセスできるようになった。

> サンプルアプリケーションで使った DB サーバー（DB エンジン）の名前と、今 Cloud9 で動作
しているバージョンはいくつか確認してみましょう。

- エンジンはMySQL。
- バージョンは以下。

```
mysql  Ver 8.0.31 for Linux on x86_64 (MySQL Community Server - GPL)
```


> DB サーバーを終了させた場合、引き続きアクセスできますか？

- 以下にて停止。

```
ActiveRecord::ConnectionNotEstablished in FruitsController#index
```

> Rails の構成管理ツールの名前は何でしたか？確認してみてください。

- bundler

> 今回の課題から学んだことを報告してください。

- 今回のアプリケーションはAPサーバーとDBサーバーで構成されている。
- どちらが止まっていてもアプリケーションは動かない。