お仕事のご依頼は[TwitterのDM](https://twitter.com/messages/compose?recipient_id=812979422554779648) 、もしくは yo@yagipy.me までお願いします。  
最終更新日: 2021/03/07

## 自己紹介
八木橋拓之(Hiroyuki Yagihashi)です。  
特にGo/Node.jsを使用したAPIサーバーやライブラリの開発、AWSを用いたインフラ構築を得意としています。  
Reactを使用したWebクライアントの開発、Go/Node.jsの他にRailsを用いたAPIサーバー開発、Androidアプリ開発も対応可能です。  
最近の業務内容としては、基本設計(要件が技術的に可能かどうかの検証、外部APIとの連携フロー作成)、詳細設計(DB設計、API設計、技術選定)、ベースコードの作成、会社単位で導入事例のない技術の検証と実装を行い、他の部分は困ったら適宜サポートするというのがメインになります。  
サポートは主にレビューやペアプロ等を通して、設計意図の共有やメンバーが設計に沿った実装を行えるようにしています。

## 興味
より多くのユーザーや開発者が使用しているサービスやライブラリを書くことに興味があります。  
多くのユーザーが存在している際に起きる技術的な問題は情報が少なく、よりチャレンジングな問題に取り組める可能性が高いと考えています。  
担当領域の広さに比例してやる気が高まる傾向があります。  
幅広い領域を担当することで、より全体最適な意思決定を行える確率が高まると考えています。  

新しい技術を触ることが好きです。  
新しい技術を使用することによって、今までは極めて困難だった実装が簡単に実装できることや開発者体験が良くなることが多く、そこに楽しみを感じています。

現在興味のある技術分野は下記になります。
- micro services
- Go
- Rust
- wasm
- web standards

## SNS
- [Twitter](https://twitter.com/yagipy_)
- [GitHub](https://github.com/yagipy)
- [Blog](https://blog.yagipy.me)

## 職務経歴
### からくり株式会社 (2019年4月 ~ 在職中)
<details>

2019年4月に新卒入社。  
テックリード(Webフロントエンド/バックエンド)、教育グループリーダー、ソフトウェアエンジニアを担当。

#### テックリードとして
<details>

Webフロントエンド/バックエンドに関する見積作成や基本設計、レビュー(詳細設計、技術選定、実装)を担当。

- open apiやGraphQL、gRPCを使用したスキーマ駆動開発の導入
  - GraphQL(gqlgen, graphql-ruby, apollo-client)の導入
  - gRPCの導入(ruby, golangのサービス間通信、grpc-gatewayを使用したHTTP通信の提供)
- terraformを使用したIaCの導入(Ansibleは導入済)
- Next.jsの導入
- Recoilの導入
- ECS on Fargateを使用した本番環境のDocker化
  - 開発環境でのみ使用されていたDockerを本番環境に導入
</details>

#### 教育グループリーダーとして
<details>

教育グループには各プラットフォームのテックリードが参加しており、会社レベルでの教育に関する施策の立案や実行を担当。  
エンジニア評価制度に関しても作成。
主に行った施策は下記になります。

- KPIの立案・作成・運用
- エンジニア評価制度(コンピテンシーマトリクス)の立案・作成・運用
- エンジニアメンターシップ制度の立案・作成・実施・運用
- 研修制度のプラッシュアップ
- テックリードによる塾形式の勉強会の立案・実施
- ライブラリ/設計比較検討会の立案・実施
</details>

#### ソフトウェアエンジニアとして
<details>

抜粋しています。  
詳細については下記ブログにまとめています。  
[2021年の詳細](https://blog.yagipy.me/2021-in-review)  
[2020年の詳細](https://blog.yagipy.me/2020-in-review)

### オンライン診療アプリ(2021/11~現在)

#### 概要  
オンライン診療を行うアプリ。
患者さん用のiOS/Androidアプリと医療従事者用のWebアプリ、システム管理者用のWebアプリを構築。

#### 役割  
- Webフロントエンド、バックエンドのエンジニアリード
  - 要件定義(お客さんとのMTG、技術的な部分に関しての質問回答、工数見積)
  - 基本設計(要件が技術的に可能かどうかの検証、外部APIとの連携フロー構築)
  - 詳細設計(DB設計、API設計、技術選定)
  - ベースコードの作成
  - 会社単位で導入事例のない技術の検証と実装
- Webフロントエンド、バックエンドのプロジェクトマネジメント(メンバー数最大6名)
  - スケジュール、進捗管理
  - 品質管理(レビュー、ペアプロ)
- 業務委託面談

#### 技術
- Go
  - gqlgen
  - ent
- GMOPayment
- Twilio
- AWS
  - ECS on Fargate
  - Aurora
- React
  - vite
  - ChakraUI

#### 担当業務  
- 基本設計(要件が技術的に可能かどうかの検証、外部APIとの連携フロー構築)
  - Twilioを使用したビデオ通話機能
  - GMOPaymentを使用したサブスクリプション課金機能
- 詳細設計(DB設計、API設計、技術選定)
- gqlgen、entを使用したベースコードの構築
- GraphQL subscriptionを使用したリアルタイムチャット機能の検証、実装

### 工事現場での無傷事故報告アプリ(2021/06~現在)

#### 概要
工事現場で無傷事故が発生した際に報告を行うモバイルアプリ、報告された内容を確認するWeb画面を作成。  
今まで会社で使用していたサーバーサイドの言語はRubyとTypeScriptでしたが、この案件で初めてGoを導入。  
ただ、社内でGoを書ける人が少なかったので、アプリケーションレイヤをマイクロサービス化し部分的かつ段階的にGoを導入。  
具体的にはゲートウェイサーバーはGo、他のサーバーは書けるメンバーが多く社内に知見がたまっているという点でRubyを採用。  
サービス間の通信はgRPCを使用。  
grpc-gatewayを使用して各クライアント(Webフロント、iOS、Android)にはREST APIを提供する形を取りました。  
このことによってgRPCを導入した影響を最小限にしつつ、スキーマファーストな開発を導入することに成功しました。  
インフラについても、今まではAWS EC2にAnsibleでプロビジョニングする形でしたが、サーバーレスかつコンテナ化を実現したいという理由で、ECS on Fargate上に構築しました。  
サーバーレスかつコンテナ化することで、インフラ管理コストの大幅な軽減、AutoScalingの容易化及び高速化、ベンダーロックインの回避を実現できました。

#### 役割
- Webフロントエンド、バックエンドのエンジニアリード
  - 要件定義(お客さんとのMTG、技術的な部分に関しての質問回答)
  - 基本設計(要件が技術的に可能かどうかの検証)
  - 詳細設計(技術選定)
  - ベースコードの作成
  - 会社単位で導入事例のない技術の検証と実装
- Webフロントエンド、バックエンドのプロジェクトマネジメント(メンバー数最大5名)
  - スケジュール、進捗管理
  - 品質管理(レビュー、ペアプロ、テスト)

#### 技術  
- gRPC
  - grpc-gateway
- Go
- Ruby
  - guard
- ECS on Fargate
- GitHub Actions
- Next.js(React)
  - Recoil
  - TailwindCSS

#### 担当業務
- 詳細設計(DB設計、API設計、技術選定)
- grpc-gatewayを使用したgatewayサーバーの構築
- Rubyを使用したgRPCサーバーの構築
- Next.jsを使用した Web クライアントの構築
- ECS on Fargateでのインフラ構築
- GitHub Actionsを使用した自動デプロイの構築
- guardを使用したRubyのgRPCサーバーのオートリロード

### 認証認可基盤システム(2020/10~現在)

#### 概要
社員が使うアプリの認証が各アプリのサーバーで実装しており、情報が散在していた。
その情報を集約することを目的に認証認可基盤を作成。
Web管理画面とAPI開発を担当。

#### 役割
- Webフロントエンド、バックエンドのエンジニアリード
  - 要件定義(お客さんとのMTG、技術的な部分に関しての質問回答)
  - 基本設計(要件が技術的に可能かどうかの検証)
  - 詳細設計(技術選定)
  - ベースコードの作成
  - 会社単位で導入事例のない技術の検証と実装
- Webフロントエンド、バックエンドのプロジェクトマネジメント(メンバー数最大2名)
  - スケジュール、進捗管理
  - 品質管理(レビュー、ペアプロ、テスト)

#### 技術
- Serverless Framework
- Node.js(TypeScript)
  - prisma
- AWS
  - Lambda
  - API Gateway
  - EC2(踏み台サーバー、管理画面のホスティングサーバーとして使用)
  - RDS
  - RDS Proxy
- React
  - Next.js
  - TailwindCSS

#### 担当業務
管理画面がセキュリテイ要件を満たすためにEC2ホスティング、API側はAPI Gateway + Lambdaのマイクロサービス構成。DBはRDS。(コネクション管理はRDS Proxyを使用しています。)  
最初は取引会社さんの方でもAWSWebコンソールでインフラを変更する可能性があるということだったので、API全体の管理ライブラリは導入せず、デプロイや環境変数の切り替えはシェルスクリプトを使用していました。  
Serverless FrameworkやAWS SAMはインフラの設定に意図しない変更が出てしまうことを懸念して導入を見送っていました。  
ですが、取引会社さんの方で変更する部分が大体分かってきたというのもあり、取引会社さんと交渉し、大きな機能追加開発が入るタイミングでServerless Frameworkを導入しました。  
導入によって基盤全体の見通しが良くなっただけではなく、属人化の排除、インフラ設定の共通化、テスト環境と開発環境での実行が容易に出来るようになりました。

### 大手ハウスメーカー顧客管理サービス(2020/2 ~ 2020/6)

#### 概要
大手ハウスメーカーと住宅を購入した顧客がコミュニケーションを取るサービス。
顧客が使用するWeb画面と大手ハウスメーカーが使用するWeb画面、API開発を担当。

#### 役割  
- エンジニア
  - Webフロントエンド
  - バックエンド

#### 技術  
- Ruby on Rails
- React
  - react-pdf
  - react-table

#### 担当業務  
- react-pdfを使用したWebフロントでのPDF生成
- 複数ファイルのアップロード機能
- react-tableを使用した週次カレンダー機能の作成  
- 各区分ごとにソートを行う処理(API)
- パフォーマンスの最適化(API)

### 宿泊者管理サービス(2020/6 ~ 2020/9)

#### 概要
Webフロントエンド(React)/バックエンド(Rails)を担当しました。

#### 役割
- Webフロントエンド、バックエンドのエンジニアリード

#### 技術
- Ruby on Rails
- React

#### 担当業務
Webフロント/バックのリードとして、技術選定からアーキテクト、実装まで一通りの工程を担当しました。
graphql-rubyを使用したGraphQLサーバーの構築、Next.jsを使用したWebクライアント構築、terraformでのインフラ構築を担当しました。

### 大手メガネメーカー店舗向けサービス(2019/6 ~ 2020/9)

#### 概要
Android(Java)/バックエンド(Rails)を担当しました。

#### 役割
- バックエンドのエンジニア
- Androidのエンジニア

#### 技術
- Ruby on Rails
- Java(Android)

#### 担当業務
バックエンド(Rails)/Android(Java)を担当。
友達招待機能のAPI実装、Railsアップグレード(4.2->5.2)、総合決済サービスを使用したクレジットカード決済のベース実装等を担当しました。
Androidは楽天Pay、LINEPayの決済機能、クレジットカードのカメラ読み取り機能の実装を担当しました。

</details>
</details>

### 株式会社taliki (2018年6月 ~ 2019年3月)
<details>

インターンとして参画。  
SNS上で応援を集められるサービス「[ちあちあ](https://prtimes.jp/main/html/rd/p/000000003.000036295.html) 」のインフラ構築を担当。

#### 使用技術
- AWS
  - EC2
  - ELB
  - Route53
  - etc...
- Nginx
- PostgreSQL

#### 担当業務
- EC2上にDjango実行環境の構築
  - DB: PostgreSQL
  - Webサーバー: Nginx
- お名前.comからRoute53へのドメイン移管
- お名前.comからRoute53へDNSを変更

</details>

### 株式会社Hatty&Co. (2018年6月 ~ 2018年10月)
<details>

1人目のエンジニアとして参画、CTOを担当。  
大学のサークルを経由してチャットできるマッチングアプリ、「Camel」の構築を担当。

#### 使用技術
- Ruby on Rails
- AWS
  - EC2
  - ELB
  - Route53
  - etc...
- Nginx
- MySQL

#### 担当業務
- 要件定義(お客さんとのMTG、技術的な部分に関しての質問回答)
- 基本設計(要件が技術的に可能かどうかの検証)
- 詳細設計(技術選定)


</details>

## 個人の活動
### 登壇
- Building markdown editor using Rust’s parser(JS Conf JP 2021)
  - [登壇資料](https://speakerdeck.com/yagipy/building-markdown-editor-using-rusts-parser)
  - [ブログ記事](https://blog.yagipy.me/jsconfjp-2021)
- OSSに貢献した話と社内での取り組みについて(技育祭LT)
  - [登壇資料](https://speakerdeck.com/yagipy/ossnigong-xian-sitahua-toshe-nei-tefalsequ-rizu-minituite)
  - [ブログ記事](https://blog.yagipy.me/geeksai-lt)
- 簡易的な推薦機能を実装する(社内LT)
  - [登壇資料](https://speakerdeck.com/yagipy/jian-yi-de-natui-jian-ji-neng-woshi-zhuang-suru)
- Git/GitHub oneliner command(社内LT)
  - [登壇資料](https://speakerdeck.com/yagipy/github-oneliner-command)

### OSS
Owner - 私自身が作成し運用しているOSSになります  
Maintainer - リポジトリに対するWrite権限を持っているOSSになります  
Contributor - コントリビュートしたことのあるOSSになります(ここでは私自身が作成したPRがマージされたことのあるOSSに限定しています)

- Owner - [maintidx](https://github.com/yagipy/maintidx)
  - maintainability indexを計測する自作の静的解析ツールです
  - 詳しくは[こちら](https://blog.yagipy.me/analyze-maintainability-index)
- Owner - [chameleon editor](https://cameleon-editor.netlify.app/)
  - 自作マークダウンエディタです
  - Rustやwasmを使用しています
  - 詳しくは[こちら](https://blog.yagipy.me/md-editor-with-rust-parser-on-the-web)
- Owner - [blog](https://blog.yagipy.me/)
  - Next.js使用、TailwindCSS使用、PWA対応、AMP対応、OGP画像の自動生成等を行っています
  - 詳しくは[こちら](https://blog.yagipy.me/build-blog)
- Maintainer - [golangci-lint](https://github.com/golangci/golangci-lint)
  - Goの静的解析ツールをまとめて実行してくれるツールです
  - [maintidx](https://github.com/yagipy/maintidx) を追加する実装をしました
- Contributor - [go-gimei](https://github.com/mattn/go-gimei)
  - レースコンディションを回避する実装をしました
- Contributor - [Node.js](https://github.com/nodejs/node)
  - fsPromise.writeFileのdata引数としてasync iteratorsをサポートする実装をしました
  - 詳しくは[こちら](https://blog.yagipy.me/nodejs-writefile-support-async-iterators)
- Contributor - [DroidKaigi conference app 2021](https://github.com/DroidKaigi/conference-app-2021)
  - ダークモードの対応や軽微な修正を行いました

### コミュニティ
- Staff - [Go Conference](https://gocon.jp) 
  - [2022 Spring](https://gocon.jp/2022spring/) から運営のお手伝いをしています
