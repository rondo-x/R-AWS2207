# R-AWS2207
## 課題提出用
### 実施内容(課題2)
- ブランチ: lecture02を作成
- lecture02.mdに講座での学びを記載(Markdown形式)
- pushの実施
- Pull Requestを発行
### 実施内容2(課題3)
- ブランチ: lecture03を作成
- lecture03.mdに課題3の内容記載
- pushの実施
- Pull Requestを発行
### 実施内容3(課題4)
- ブランチ: lecture04を作成
- lecture04_cnct.pngを作成(RDSへ接続時画像)
- lecture04.drawio.pngを作成(構成図)
- pushの実施
- Pull Requestを発行
### 実施内容4(課題5)
- サンプルアプリをデプロイする (rails/unicorn/nginxを使用する)

詳細
1. APとWeb Server を同一マシンで構築し、ALBを設定して公開する 
2. APとWeb Server を別マシンで構築し、Web ServerにALBを設定して公開する 
3. S3にCLIで画像をコピーし、サンプルアプリで参照・表示する

### 実施内容5(課題10)
- 課題5のインフラ構成図(lecture05_2)を自動で再現する (Cloud Formationを使用する)

テンプレート補足
1. 「rt_main.yml」で依存関係を定義し、以下ymlのスタックも生成
2. 「rt_vpc.yml」でVPC,各種Subnetを生成
3. 「rt_ec2web.yml」でWeb Serverを生成
4. 「rt_ec2ap.yml」でAP Serverを生成
5. 「rt_Rds_mysql.yml」でDB(MySQL)を生成
6. 「rt_alb.yml」でload Balancer(ALB)を生成
