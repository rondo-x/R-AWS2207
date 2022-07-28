## 第3回 課題
---
## 1. AP サーバーの調査
### AP サーバーの名前とバージョン
　　AP サーバーの名前: Puma <br>
　　バージョン: 5.6.4


### AP サーバーを終了させた場合、引き続きアクセスできるか
　　結果: アクセスできない


## 2. DB サーバーの調査
　　DBサーバーの名前(DBエンジン): MySQL <br>
　　Cloud9上で動作させている現在のバージョン: 8.0.29 <br>
　　　　for Linux on x86_64 (MySQL Community Server - GPL) <br>
　　DBサーバーを終了させた場合、引き続きアクセスできるか: アクセスできない <br>
　　　　Error表示 : ActiveRecord::ConnectionNotEstablished
　　　　　　　　　　Can't connect to local MySQL server through socket '/var/lib/mysql/mysql.sock' (2)

## 3. Rails構成管理ツール
 - ツール名: Bundler


## 4. 今回の課題で学んだこと
 Webアプリとは何かを必要な「リソースの準備」とそれらの「動作設定」を通じて学ぶことができた。 <br>
 エラー解決に向けた対応で、つまずいた分だけ動きの理解につながった。 <br>
 <br>
 **今回の反省** <br>
 nvmのバージョンが、再起動後に古いデフォルトバージョンに自動で戻っていることにしばらく気づかなかった。 <br>
 結果、これに連鎖してインストールしたはずのnpmやyarnが見つからず、事態の収集に時間を要することとなった。 <br>
 各ツール特性の把握も当然だが、Linux学習の必要性を強く実感した。
