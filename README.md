# 職務経歴書

## 概要・強み

現職では自社製の営業支援サービスの新機能開発やRDBテーブルの再設計・APIレスポンスの高速化などを主として取り組んでいます。  
前職ではSNSサービス新規開発に参画し、クラウドインフラ (AWS・Heroku) とCI/CDの整備・API開発・管理画面のWebフロントエンド開発など行っていました。  

自分のスキル分布を一言で表すとバックエンド寄りのフルスタックエンジニアだと思います。

### バックエンド

一番自信のある領域で、Ruby on RailsとPHP Laravelの経験が主になります。  
品質を担保するためにテストコードと一緒に実装を進めることができます。  
RDBについてはものすごく強いということはないですが、アプリケーションコードのバリデーションだけでなく外部キー制約・ユニーク制約・NOT NULL制約などをしっかりと活用することでデータの不整合を未然に防ぐ、また、検索対象カラムにインデックスを貼って高速化したり、無駄なクエリ発行を回避する記述を意識することはできます。  
よりRDBに精通することは自身の今後の課題だと思っています。

### インフラ

専らクラウドとコンテナ技術の経験になります。  
クラウドの経験AWSメインです。実務ではS3・CloudFront・ALB・ECS Fargateなどを設定した経験があります。
コンテナ技術はDockerfileやdocker-compose.ymlを0→1で書く、また、CIの設定ファイルを書くことはできます。  
Kubernetesはそこまでですが、ステージング環境でコンテナごとのリソースを増減する、 `kubectl exec` でコンテナ上でコマンドを実行する程度のことは現職で行っています。

### フロントエンド

TS+React+Redux・Vue+Vuex・AngularJSの実務経験があり、例えばSPAの状態管理を読み解いて追加・修正することは得意だと思います。     
ただしデザインやCSSは苦手としており得意なメンバーに頼ることが多いです。

### 技術負債・レガシーの解消

その他私の強みとしては技術負債・レガシーをできるだけ解消しようとすることだと思います。  

例えば現職ではLinterやフォーマッターが導入されていない (正確には導入していたが機能していない) 状態だったので私がメインプロジェクト外で導入を進行しました。一度にすべてのLintルールをONにして変更を加えることはあまりに差分が多くなり難しかったので、Pull Requestを細かく分けルールを1つずつONにしていきました。  
段階導入を行ったことで他のメンバーに負担をかけすぎない形でコーディングルールの統一ができたと思います。
  
また、DBにMySQLを採用していますが私が参画した時点で外部キーをはじめとする制約がほとんど存在しない状態で、これについてはさすがに全体を改善することはできませんでしたが、自分が担当した機能領域についてはCTOの確認をとりつつ不正レコードを削除するデータパッチを当てて外部キー制約を追加しました。  

前職ではDocker採用実績はありませんでしたが私がDockerfile・docker-compose.ymlの整備、そこからのCI/CD環境の構築を行っていました。  

これらは特に高度な技術力を必要としない取り組みでしたが、他の開発メンバーはなかなか着手していない様子だったので、こういった改善を実行に移すことは私の強みなのかなと思っています。

## スキル

### 言語

- PHP
- Ruby
- JavaScript
- TypeScript
- Java

### フレームワーク/プラットフォーム

- Laravel
- Ruby on Rails
- Vue.js
- React + Redux
- AngularJS

### その他

- AWS
- Docker
- Kubernetes
- VirtualBox + Vagrant

## 職務経歴

### 2019/08 - : 自社サービス企業

#### 自社製SFAの改修・新機能開発

##### 使用技術

- Ruby (Rails)
- TypeScript (React + Redux)
- MySQL
- AWS
  - EKS/RDS/Elasticache/S3など
- Docker
- GitHub

##### チーム構成・ポジション

- チームリード兼フロントエンドエンジニア1名
- フルスタックエンジニア1名
- バックエンドエンジニア1名（私）
- デザイナー1名
- QAエンジニア1名

##### 仕事内容

- Webバックエンド領域をメインで担当しました。
  - Ruby on Railsのアプリケーションレイヤー開発。RSpecを用いたテストケース記述。
  - MySQLテーブル設計・改修。
- SQL実行時間の計測・チューニングを行いました。
  - パフォーマンス要件がシビアだったため。
  - 集計結果を保存するテーブル非正規化設計を行いました。
  - 改修前、レスポンスに20~30秒かかっていた機能を2秒程度に短縮しました。
- バックエンドメインでしたが、担当機能に紐づくReactフロントエンドの改修も一部担当しました。

### 2017/11 - : 受託開発企業

#### マッチングサービス新規開発（受託）

##### 使用技術

- PHP（Laravel）
- JavaScript（Vue.js）
- AWS ECS Fargate
- AWS ALB
- AWS CodeDeploy
- AWS S3
- AWS Cloud Front
- Docker
- Bitbucket Pipelines

##### チーム構成

- リーダー兼バックエンドエンジニア1名
- フロントエンドエンジニア1名
- フルスタックエンジニア1名（私）

##### ポジション

フルスタックエンジニア

##### 仕事内容

- Vue+Vuex+VueRouterを用いたSPA実装
- Laravel APIサーバの設計・実装
- マッチングサービスのためLaravelのGuard機能を使ってマルチ認証を実装しました。
- クラウド・CI領域については特に私が主導しました。
- Dockerfileの作成、CIによるECRへのDockerイメージ自動プッシュ環境の整備、ECS Fargateの導入・整備を行いました。また、CodeDeployと連携を行いBlueGreenデプロイを実現しています。

#### SNS サービスの新規開発 （自社）

自社サービスの SNS を 0→1 開発中。

##### 使用技術

- iOS, Androidアプリ
- PHP Laravel
- Postgres
- Heroku
- AWS S3, CloudFront, SNS
- Elasticsearch
- BitbucketPipelines CI

##### チーム構成

- iOSエンジニア1名
- バックエンドエンジニア2名（私）

##### ポジション

バックエンドエンジニア

##### 仕事内容

- RDB設計、 Laravelを用いたAPIサーバの設計・実装を行っています。
- インフラ領域は特に私が主導しています。チームの人数が少数であったことから、サーバ運用の手間を極力減らしたいと思い、Herokuをメインとして足りない機能をAWSのサービスで補うというインフラ選定を行いました。
- 開発環境・本番環境構築・AWS S3/CluoudFront/SNS のセットアップ・AWS IAMの権限設定等を行いました。
- 開発環境はDocker化を行い、AWSのサービスもLocalStackでモック化し、ローカルで開発を完結できるよう整備しました。
- 位置情報を含めた柔軟な検索が必要となったため、Elasticsearchをキャッチアップし導入しました。ローカル開発環境はLocalStack、本番はHerokuのBonsai Elasticsearchアドオンを使用しています。
- BitbucketPipelinesを用いてPhanによる静的解析・PHPUnitによるテスト→Herokuデプロイを行うCI環境を整備しました。CI用のDockerfile作成も担当しました。

#### モバイルアプリ+API サーバ改修 （受託）

発注元の自社サービス改修プロジェクト。

##### 使用技術

- Cordova モバイルアプリ
- Java Struts2
- MySQL

##### 私のポジション

- フルスタックエンジニア。
- Cordova/Monaca を用いたモバイルアプリ開発、Java を用いた API サーバ開発を行っていました。
- 社内で私一人で担当していたため、要件定義からテストまで従事しており、要件や納期の調整も行いましたので技術以外の面も伸ばせたかなと思います。
- Cordova は要領を掴むまでかなり苦戦しましたが、バックエンド一辺倒だった自分のスキルの幅が広がった点は良かったと思っています。

## 興味があり個人的に検証しているもの

強い静的型付け+関数型パラダイムを持った言語に興味があります。  
単純に業務で触る機会がない言語への興味本位ということもありますが、上を満たすような言語は一人で書いていてもコンパイルエラーを通じて機械的にコードレビューを受けることができるので自己成長につながるとも考えています。

- Rust
  - actix-web/chrono/tokio/serdeなど
- Elm

## 業務外の成果物

### ブログなど

| key         | value                                             |
| ----------- | ------------------------------------------------- |
| Medium      | [@dyoshikawa](https://medium.com/@dyoshikawa)     |
| Qiita       | [dyoshikawa](https://qiita.com/dyoshikawa)        |
| Speakerdeck | [dyoshikawa](https://speakerdeck.com/dyoshikawa)  |
| はてなブログ  | [dyoshikawa's blog](http://dyoshikawa.hatenablog.com/)   |

### AWS Serverless Uploader

- [デモ](https://aws-serverless-uploader.netlify.com/)
- フロントエンド React, Netlify
  - [GitHub](https://github.com/dyoshikawa/aws-serverless-uploader-frontend)
- バックエンド AWS APIGateway, Lambda（Go）, DynamoDB
  - [GitHub](https://github.com/dyoshikawa/aws-serverless-uploader-go)

## 登壇歴

| Date      | Event                                                                                   | Slide                                                                                |
| --------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| 2017/12/9 | [広フロ交流会+忘年会](https://hfe.connpass.com/event/72073/)                               |                                                                                      |
| 2018/1/9  | [【ハンズオン】Docker 超入門](https://h-kkb.connpass.com/event/74291/)                     | [hkkb-180109-start-docker](https://github.com/dyoshikawa/hkkb-180109-start-docker)   |
| 2018/3/26 | [CloudGarage Deep Meetup in Hiroshima](https://cloudgarage.connpass.com/event/81202/)   |                                                                                      |
