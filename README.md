# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|dyoshikawa|
|Medium|[@dyoshikawa](https://medium.com/@dyoshikawa)|
|Twitter|[@dyoshikawa](https://twitter.com/dyoshikawa)|
|Qiita|[dyoshikawa](https://qiita.com/dyoshikawa)|
|Speakerdeck|[dyoshikawa](https://speakerdeck.com/dyoshikawa)|

## スキル

太字は業務経験有。

### 言語

- プログラミング言語
  - **PHP**
  - Ruby
  - Python
  - **JavaScript**
  - TypeScript
  - **Java**
  - Golang

- 日本語
  - ネイティブ
- 英語
  - スピーキング・リスニングはかなり苦手。リーディングは必要最低限レベル。
  - 公式ドキュメント、Githubのissue、Stack Overflowの回答を読み問題を自己解決できる。

### フレームワーク/プラットフォーム

- **Laravel5**
- Rails5
- Gin
- **Vue.js**
- Nuxt.js
- **AngularJS**
- **Cordova**
- **Struts2**

### その他

- **Git**
- **AWS**
- GCP
- Firebase
- **Heroku**
- **Vagrant**
- **Docker**
- **CircleCI**

## 強み

- インフラ構築からサーバーサイドアプリケーション開発までカバーしているWebバックエンド開発者であること。

## やったことはないが興味があるもの

- 言語
  - Scala
  - Haskell
  - Rust
  - Elixir
- フレームワーク
  - Play
  - Yesod
  - Rocket
  - Phoenix
- インフラ
  - Kubernetes
  - AWS Fargate
- その他
  - Fluentd/ElasticSearch/Kibanaを用いたログ分析
  - 機械学習 (各クラウドサービスのAPI/TensorFlow/Keras)
  - マイクロサービス (gRPC)
  
### 登壇歴

|Date|Event|Slide|
|----|-----|-----|
|2017/12/9|[広フロ交流会+忘年会](https://hfe.connpass.com/event/72073/)||
|2018/1/9|[【ハンズオン】Docker超入門](https://h-kkb.connpass.com/event/74291/)|[hkkb-180109-start-docker](https://github.com/dyoshikawa/hkkb-180109-start-docker)|
|2018/3/26|[CloudGarage Deep Meetup in Hiroshima](https://cloudgarage.connpass.com/event/81202/)||

## 職務経歴

### 2017/11 - :  Web開発

職務: バックエンドエンジニア

### Web通知サービスのリプレイス (自社)
- 使用技術
  - PHP(Laravel, PHPUnit)
  - JavaScript(Vue.js, Jest)
  - Heroku
  - CircleCI
- ポジション/仕事内容
  - 技術選定・設計から中心となって関わる。
  - 開発についてもフロントエンド・サーバーサイド・インフラ・CI整備まで一人で担当。
  - サービスの管理画面が複雑だったため、SPA化の必要性を感じ、Laravelオンリーの構成をVue.js(SPA)+Laravel(APIサーバ)に変更。インフラについては、一人プロジェクトであり手間をかけられないため、PaaSであるHerokuを選定。
  - 品質を保つためにCircleCIでテストコード(PHPUnit、Jest)を回してからデプロイするように整備。
  - コード規約もPHPCodeSniffer、PHPStan、ESLintで自動監視。
  - 自社ではCIデプロイの整備やテストコードを書く文化が浸透していないため、導入技術は社内で共有。

### SNSサービスの新規開発 (自社)

- 使用技術
  - iOS, Android
  - PHP (Laravel)
  - Heroku
  - AWS
  - BitbucketPipelines CI
- ポジション/仕事内容
  - サーバサイドアプリからインフラ領域までを担当。
  - サーバーサイドはチームの一員としてDB設計からLaravelのAPI開発まで関わる。
  - インフラは自分が中心となって取り組み、開発環境・本番環境構築・AWS S3/CluoudFront/SNS のセットアップ・AWS IAMの権限設定等を行う。
  - BitbucketPipelinesを用いてPHPUnit実行→Herokuデプロイを行うCI環境を整備。CI用のDockerイメージも作成。

### モバイルアプリ+APIサーバ改修 (受託)

- 使用技術
  - Cordova
  - AngularJS
  - Java (Struts2)
  - MySQL
- ポジション/仕事内容
  - フルスタックエンジニア。
  - Cordova/Monacaを用いたモバイルアプリ開発。
  - Javaを用いたAPIサーバ開発。
  - 自社からは一人で担当。要件定義からテストまで携わる。

### 2017/2 - 2017/10: 業務システム受託

職務: PG

#### 在庫管理システム改修 (受託)

- 使用技術
  - WindowsSever
  - VB.NET
  - SQLServer
- ポジション/仕事内容
  - 初めての実務経験。
  - 未経験者だった自分にとって静的型言語とSQLの業務経験を積めた点は非常に貴重だった。
  - 他人の書いたコードを読み、それを修正するという実務ならではの重要な経験を積めた。
