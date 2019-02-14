# 職務経歴書

## 基本情報

| key         | value                                             |
| ----------- | ------------------------------------------------- |
| Medium      | [@dyoshikawa](https://medium.com/@dyoshikawa)     |
| Twitter     | [@dyoshikawa](https://twitter.com/dyoshikawa1993) |
| Qiita       | [dyoshikawa](https://qiita.com/dyoshikawa)        |
| Speakerdeck | [dyoshikawa](https://speakerdeck.com/dyoshikawa)  |

## スキル

太字は業務経験有。

### 言語

- **PHP**
- Ruby
- **JavaScript**
- TypeScript
- **Java**
- Go

### フレームワーク/プラットフォーム

- **Laravel5**
- Rails5
- Gin
- **Vue.js**
- React
- **AngularJS**
- **Cordova**

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

- インフラ構築からサーバーサイドアプリケーション開発までカバーしている Web 開発者であること。

## 興味があり個人的に検証しているもの

- Go
  - （理由）
  - 業務で動的言語を書くことが多いので、静的型付き言語を書く感覚も養うため
  - シンプルな言語仕様、パフォーマンスの良さ、コンパイルが非常に早い等ランタイムの特徴に魅力を感じる
- サーバーレスアーキテクチャ（AWS APIGateway, Lambda, DynamoDB or Firebase）
  - （理由）
  - インフラは自分で頑張るよりクラウドサービスの凄腕インフラエンジニア達に任せた方が合理的ではと思い始めた
  - マイクロサービスアーキテクチャとの親和性が高い
- React
  - （理由）
  - Vue と比較してイミュータブル重視、TypeScript 使用時に JSX で型チェックが効く → 堅い開発が可能そうに思える
  - React Native, React VR の存在

## 個人開発の成果物

### 超シンプル家計簿

- [デモ](https://cho-simple-kakiebo.firebaseapp.com)
- React, Firebase
  - [GitHub](https://github.com/dyoshikawa/cho-simple-kakeibo)

### AWS Serverless Uploader

- [デモ](https://aws-serverless-uploader.netlify.com/)
- フロントエンド React, Netlify
  - [GitHub](https://github.com/dyoshikawa/aws-serverless-uploader-frontend)
- バックエンド AWS APIGateway, Lambda（Go）, DynamoDB
  - [GitHub](https://github.com/dyoshikawa/aws-serverless-uploader-go)

## 興味はあるが（あまり）手を着けられていないもの

- Scala, Haskell, Rust
- Fluentd/ElasticSearch/Kibana を用いたログ分析
- 機械学習 （各クラウドサービスの API/TensorFlow/Keras）
- マイクロサービス （gRPC）

## 登壇歴

| Date      | Event                                                                                   | Slide                                                                                |
| --------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| 2017/12/9 | [広フロ交流会+忘年会]（https://hfe.connpass.com/event/72073/）                          |                                                                                      |
| 2018/1/9  | [【ハンズオン】Docker 超入門]（https://h-kkb.connpass.com/event/74291/）                | [hkkb-180109-start-docker]（https://github.com/dyoshikawa/hkkb-180109-start-docker） |
| 2018/3/26 | [CloudGarage Deep Meetup in Hiroshima]（https://cloudgarage.connpass.com/event/81202/） |                                                                                      |

## 職務経歴

### 2017/11 - : Web 開発企業

職務: フルスタックエンジニア

### マッチングサービス新規開発（受託）

#### 使用技術

- PHP（Laravel）
- JavaScript（Vue.js）
- AWS Elastic Beanstalk
- AWS S3
- AWS Cloud Flont
- Docker
- Bitbucket PIpelines

#### チーム構成

- リーダー兼バックエンドエンジニア 1 名
- フロントエンドエンジニア 2 名（私）

#### 私のポジション

- フロントエンドエンジニア。
- Vue+Vuex+VueRouter を用いた SPA 実装が主ですが、クラウドインフラ・CI 周りの整備については私が主導しました（社内では比較的私が詳しかったため）。
- Laravel API サーバの設計・実装はリーダーの担当領域でしたが、API の仕様を詰める際は意見を出します。

### Web 通知サービスのリプレイス （自社）

#### 使用技術

- PHP(Laravel, PHPUnit)
- JavaScript(Vue.js, Jest)
- Heroku
- CircleCI

#### チーム構成

- フルスタックエンジニア 1 名（私）

#### 私のポジション

- 技術選定・設計から中心となって関わり、実装もフロントエンド・サーバーサイド・インフラ・CI 整備まで一人で担当。
- サービスの管理画面が複雑だったため、SPA 化の必要性を感じ、Laravel オンリーの構成を Vue.js(SPA)+Laravel(API サーバ)に変更。
- インフラについては、一人プロジェクトであり手間をかけられないため、PaaS である Heroku を選定。また、品質を保つために CircleCI でテストコード(PHPUnit、Jest)を回してからデプロイするように整備。
- コード規約は PHPCodeSniffer、PHPStan、ESLint で自動監視。
- 社内では CI デプロイの整備やテストコードを書く文化が浸透していないため、毎月の会議で導入技術について共有するようにしています。

### SNS サービスの新規開発 （自社）

自社サービスの SNS を 0→1 開発中。

#### 使用技術

- OS, Android アプリ
- PHP Laravel
- Postgres
- Heroku
- AWS S3, CloudFront, SNS
- Bitbucket Pipelines

#### チーム構成

- iOS エンジニア 1 名
- バックエンドエンジニア 2 名（私）

#### 私のポジション

- バックエンドエンジニア。
- RDB 設計は主導する立場ではありませんが意見は出しています。
- Laravel を用いた API サーバの設計・実装を行っています。
- インフラ周りは私が主導しており、チームの人数が少数であったことから、サーバ運用の手間を極力減らしたいと思い、Heroku をメインとして足りない機能を AWS のサービスで補うというインフラ選定を行いました。
- 開発環境・本番環境構築・AWS S3/CluoudFront/SNS のセットアップ・AWS IAM の権限設定等を行いました。
- Bitbucket Pipelines を用いて PHPUnit 実行 →Heroku デプロイを行う CI 環境を整備しました。CI 用の Dockerfile 作成も担当しました。

### モバイルアプリ+API サーバ改修 （受託）

発注元の自社サービス改修プロジェクト。

#### 使用技術

- Cordova モバイルアプリ
- Java Struts2
- MySQL

#### 私のポジション

- フルスタックエンジニア。
- Cordova/Monaca を用いたモバイルアプリ開発、Java を用いた API サーバ開発を行っていました。
- 社内で私一人で担当していたため、要件定義からテストまで従事しており、要件や納期の調整も行いましたので技術以外の面も伸ばせたかなと思います。
- Cordova は要領を掴むまでかなり苦戦しましたが、バックエンド一辺倒だった自分のスキルの幅が広がった点は良かったと思っています。
