お仕事のご依頼は[TwitterのDM](https://twitter.com/messages/compose?recipient_id=812979422554779648) 、もしくは yo@yagipy.me までお願いします。  
最終更新日: 2022/10/16

## 目次
- 自己紹介
- 興味
- 各種リンク
- 職務経歴
  - からくり株式会社 (2019年4月 ~ 在職中)
  - 株式会社taliki (2018年6月 ~ 2019年3月)
  - 株式会社Hatty&Co. (2018年6月 ~ 2018年10月)
- 個人の活動
  - 登壇
  - OSS
  - OSS以外の個人プロジェクト
  - コミュニティ

## 自己紹介

<details>

八木橋拓之(Hiroyuki YAGIHASHI)です。  
バックエンドエンジニアとして、主にGo/Node.jsを使用したAPIサーバーやライブラリの開発、AWSを用いたインフラ構築を得意としています。  
Reactを使用したWebクライアントの開発、Go/Node.jsの他にRailsを用いたAPIサーバー開発、Androidアプリ開発も実務経験があります。  
直近の業務内容は、見積作成、設計、ベースコードの作成、会社単位で導入事例のない技術の検証と実装を行いつつ、他メンバーのサポートをするというのがメインになります。  
サポートは主にレビューやペアプロ等を通して、設計意図の共有やメンバーが設計に沿った実装を行えるようにしています。  
上記をWebフロントとバックエンド両方とも行っていましたが、2022/03くらいからWebフロントは全体のレビューをするのみになり、バックエンドを中心に行っています。

</details>

## 興味
より多くのユーザーや開発者が使用しているサービスやライブラリを書くことに興味があります。  
多くのユーザーが使用している際に起きる技術的な問題は情報が少なく、よりチャレンジングな問題に取り組める可能性が高いと考えています。  
担当領域の広さに比例してやる気が高まる傾向があります。  
幅広い領域を担当することで、より全体最適な意思決定を行える可能性が高まると考えています。  
新しい技術を触ることが好きです。  
新しい技術を使用することによって、今までは極めて大変だった実装が簡単に実装できることや開発者体験が良くなることが多く、そこに楽しみを感じています。

現在興味のある技術領域は下記になります。
- 分散システム
- コンパイラ(主にメモリ管理)
- Go
- Rust
- Web Assembly
- Web標準

## 各種リンク
- [GitHub](https://github.com/yagipy)
- [Twitter](https://twitter.com/yagipy_)
- [Blog](https://blog.yagipy.me)
- [SpeakerDeck](https://speakerdeck.com/yagipy)

## 職務経歴
### からくり株式会社 (2019年4月 ~ 在職中)

<details>

2019年4月に新卒入社。  
テックリード(Webフロントエンド/バックエンド)、教育グループリーダー、ソフトウェアエンジニアを担当しています。

#### テックリードとして (2021年4月 ~ 在職中)

<details>

Webフロントエンド/バックエンドに関する見積作成や設計、技術選定、レビュー(主に実装)、ドキュメンテーションを担当しています。

TODO: 更新する
- open apiやGraphQL、gRPCを使用したスキーマ駆動開発の導入
  - GraphQL(gqlgen, graphql-ruby, apollo-client)の導入
  - gRPCの導入(ruby, golangのサービス間通信、grpc-gatewayを使用したHTTP通信の提供)
- terraformを使用したIaCの導入(Ansibleは導入済)
- Next.jsの導入
- Recoilの導入
- ECS on Fargateを使用した本番環境のDocker化
  - 開発環境でのみ使用されていたDockerを本番環境に導入

</details>

#### 教育グループリーダーとして (2020年9月 ~ 在職中)
<details>

### 概要
教育グループでは、会社レベルでの教育に関する施策の立案や実行を担当しました。  
エンジニア評価制度に関しても作成しました。  
施策の立案や実行の過程で、"学習する組織"や"リファクタリング•ウェットウェア"、"成人発達理論による能力の成長"という本を読み、体系的な能力開発に関する知識を得ることができました。  
主に行った施策は下記になります。

- KGI/KPIの立案・作成・運用
- エンジニア評価制度(コンピテンシーマトリクス)の立案・作成・運用
- エンジニアメンターシップ制度の立案・作成・実施・運用
- 研修制度のプラッシュアップ
- テックリードによる塾形式の勉強会の立案・実施
- ライブラリ/設計比較検討会の立案・実施
</details>

#### ソフトウェアエンジニアとして (2019年4月 ~ 在職中)
<details>

プロジェクトは抜粋しています。  
各プロジェクトの項目は"プロジェクト概要と担当領域"、"役割"、"担当工程"、"使用技術"、"担当業務"で構成されていますが、
リードエンジニアを担当したプロジェクトのみ"利用技術や技術選定に関する思考と行動"を追加しています。  

詳細については下記ブログにまとめています。  
[2021年の詳細](https://blog.yagipy.me/2021-in-review)  
[2020年の詳細](https://blog.yagipy.me/2020-in-review)

### オンライン診療アプリ(2021/11~現在)

#### プロジェクト概要と担当領域
オンライン診療や医師とのチャットを行うことができるアプリです。
患者用のWebアプリと医療従事者用のWebアプリ、システム管理者用のWebアプリ、各Webアプリとネイティブアプリに提供するAPIサーバー、インフラ構築を担当しました。

#### 利用技術や技術選定に関する思考と行動
工事現場での無傷事故報告アプリで発生した問題の解決を試みました。
TODO: 更新する

#### 役割  
- Webフロントエンド/バックエンドのリードエンジニア
- Webフロントエンド/バックエンドのプロジェクトマネジメント(メンバー数最大6名)
  - スケジュール/進捗管理
  - 品質管理(レビュー、ペアプロ)
  - 業務委託面談

#### 担当工程
- 要件定義
- 設計
- 実装
- テスト

#### 使用技術
- Go
  - gqlgen
  - ent
- GMOPayment
- Twilio
- AWS
  - ECS on Fargate
  - Aurora(MySQL互換)
- React
  - vite
  - ChakraUI

#### 担当業務  
- お客さんとのMTG
  - 技術的な部分に関しての質問回答
- 工数見積
- 要件が技術的に可能かどうかの検証、外部APIとの連携フロー構築、DB設計、API設計、技術選定
- 外部APIとの連携フロー構築
- Twilioを使用したビデオ通話機能
- GMOPaymentを使用したサブスクリプション課金機能
- 詳細設計(DB設計、API設計、技術選定)
- gqlgen、entを使用したベースコードの構築
- 会社単位で導入事例のない技術の検証と実装
- GraphQL subscription、redis pubsub、goroutineを使用したリアルタイムチャット機能の検証、実装

### 工事現場での無傷事故報告アプリ(2021/06~現在)

#### プロジェクト概要と担当領域
工事現場で無傷事故(ヒヤリハット)が発生した際に報告を行うアプリ。
報告された内容を確認する管理者用のWeb画面、ネイティブアプリと管理者用Web画面に提供するAPI開発を担当。  

#### 利用技術や技術選定に関する思考
大きく3つのチャレンジを行いました。
- Goの導入
- gRPCを使用したスキーマ駆動開発の導入
- ECS on Fargateを使用した本番環境のDocker化

Goの導入から説明します。
今まで会社がメインで使用していたサーバーサイドの言語はRubyでしたが、この案件で初めてGoを導入しました。  
導入した理由としては、
ただ、社内でGoを書ける人が少なかったので、アプリケーションレイヤをマイクロサービス化し部分的かつ段階的にGoを導入しました。  
具体的にはゲートウェイサーバーはGo、他のサーバーは書けるメンバーが多く社内に知見がたまっているという点でRubyを採用しました。

gRPCを使用したスキーマ駆動開発の導入について説明します。
APIのインターフェースはフロントエンドとバックエンドの間で共通の認識を持つ必要があります。
今までのプロジェクトではAPIのインターフェースはドキュメントか口頭によって共有されていました。
しかし、下記のような問題が発生していました。
- ドキュメント
  - APIの数が多くなると管理が難しくなり、実装とドキュメントの内容が乖離してしまう
  - 人によって書き方にばらつきがあり、認識を合わせるのに時間がかかる
- 口頭
  - 共有された内容を後から参照できない

上記の問題を解決するために、gRPCを使用したスキーマ駆動開発を導入しました。
grpc-gatewayを使用して各クライアント(Webフロント、iOS、Android)にはREST APIも提供する形を取りました。  
このことによってgRPCを導入した影響を最小限にしつつ、スキーマファーストな開発を導入することに成功しました。

ECS on Fargateを使用した本番環境のDocker化について説明します。
今まではAWS EC2にAnsibleでプロビジョニングする形でしたが、サーバーレスかつコンテナ化を実現したいという理由で、ECS on Fargate上に構築しました。
サーバーレスかつコンテナ化することで、インフラ管理コストの大幅な軽減、AutoScalingの容易化及び高速化を実現できました。

#### 役割
- Webフロントエンド、バックエンドのリードエンジニア
- Webフロントエンド、バックエンドのプロジェクトマネジメント(メンバー数最大5名)
  - スケジュール、進捗管理
  - 品質管理(レビュー、ペアプロ)

#### 担当工程
- 要件定義
- 設計
- 実装
- テスト

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
- GitHub Actionsを使用した自動デプロイフローの構築
- guardを使用したRubyサーバーのオートリロード

### 認証認可基盤システム(2020/10~現在)

#### プロジェクト概要と担当領域
社員が使うアプリの認証が各アプリのサーバーで実装しており、情報が散在していた。
その情報を集約することを目的に認証認可基盤を作成。
Web管理画面とAPI開発を担当。

#### 利用技術や技術選定に関する思考
インフラ構成や言語については、お客さんの方から要望があったため、要望に答える形で実装しました。
APIはAPI Gateway + Lambdaの構成になっています。
DBはRDSを使用しています。(コネクション管理はRDS Proxyを使用しています。)
管理画面は"アクセスをプライベートネットワークに閉じたい"という要件があったため、会社でよく使っていたS3の静的Webサイトホスティングを使用して、プライベートIPのみを設定できないか調査を行いました。
上記を調査しているタイミングでAWS PrivateLink for Amazon S3の一般提供が開始され、これで可能になると考えていたのですが、静的WebサイトホスティングはPrivateLinkに対応していないことがわかりました。
最終的にはEC2でホスティング(Nginxを使用しています)を行いました。

最初はお客さんの方でもAWS Web コンソールでインフラを変更する可能性があるということだったので、API全体の管理ライブラリは導入せず、デプロイや環境変数の切り替えはシェルスクリプトを独自に組んで使用していました。  
Serverless FrameworkやAWS SAMはインフラの設定に意図しない変更が出てしまうことを懸念して導入を見送っていました。  
ですが、取引会社さんの方で変更する部分が大体分かってきたというのもあり、取引会社さんと交渉し、大きな機能追加開発が入るタイミングでServerless Frameworkを導入しました。  
導入によって基盤全体の見通しが良くなっただけではなく、属人化の排除、インフラ設定の共通化、テスト環境と開発環境での実行が容易に出来るようになりました。
なお、上記のタイミングでJavaScriptからTypeScriptへの移行も行い、より安全に開発を行えるようになりました。

Webアプリは新しくRecoilを導入しました。

#### 役割
- Webフロントエンド、バックエンドのリードエンジニア
- Webフロントエンド、バックエンドのプロジェクトマネジメント(メンバー数最大2名)
  - スケジュール、進捗管理
  - 品質管理(レビュー、ペアプロ)

#### 担当工程
- 要件定義
- 設計
- 実装
- テスト

#### 使用技術
- Serverless Framework
- Node.js(JavaScript、TypeScript)
  - prisma
  - ldapjs
  - bcryptjs
  - samba-client
- AWS
  - Lambda
  - API Gateway
  - EC2(踏み台サーバー、管理画面のホスティングサーバーとして使用)
  - RDS
  - RDS Proxy
- Nginx
- React
  - Next.js
  - Recoil
  - TailwindCSS

#### 担当業務
- 技術選定
- ベースコードの作成
- バッチ処理の実装 
- Recoil

### 宿泊者管理サービス(2020/6 ~ 2020/9)

#### プロジェクト概要と担当領域
宿泊者の入退室を管理したり、管理者とチャットやビデオ通話を行うことが出来るアプリ。
管理者が使用するWebアプリとAPIサーバーを担当。

#### 利用技術や技術選定に関する思考
大きく3つのチャレンジを行いました。
- GraphQLの導入
- Next.jsの導入
- Terraformを使用したIaCの導入

GraphQLの導入ですが、大手ハウスメーカー顧客管理サービスで発生していた課題を解決することを試みました。
主に問題となっていたのは下記の3つです。
- 画面の表示要素を変えるたびに、API側のコードを修正する必要がある
- 1画面で複数のAPIを叩いており、画面描画に遅れが出ていた/フロント側で取得した値を管理しづらい
- APIが様々な画面で叩かれているため、どのレスポンスの値がどこで使われているか把握しづらく、レスポンスの値を削除しにくい

解決策として、下記の2つを候補として考えました。
- RESTにextendsやfieldsというリクエストパラメータを追加し、レスポンスをリクエストパラメータに応じて変更するようにする
- GraphQLを使用する

どちらでも解決可能でしたが、下記3つの理由によりGraphQLを採用しました。
- アプリのサイズが他アプリより大きくなく、挑戦的な技術選定が可能であるため
- 今後社内でGraphQLを導入する可能性を考え、小規模なアプリでGraphQLを使用することで、影響範囲を最小限にしつつ、社内にGraphQLの知見をためることができる
- コアロジックを分離しておけば低コストでRESTへの切り替えが可能であると判断したため

その結果、問題が解決されただけではなく、今後の開発においてもGraphQLという選択肢を取ることが以前より容易になり、会社全体としても問題解決の幅が広がったと考えています。

#### 役割
- Webフロントエンドのリードエンジニア
- バックエンドのリードエンジニア

#### 担当工程
- 要件定義
- 設計
- 実装
- テスト

#### 使用技術
- Ruby on Rails
  - graphql-ruby
- React
  - Next.js
- terraform

#### 担当業務
- graphql-rubyを使用したGraphQLサーバーのベースコード作成
- Next.jsを使用したWebアプリのベースコード作成
- terraformを使用したインフラ構築

### 大手ハウスメーカー顧客管理サービス(2020/2 ~ 2020/6)

#### プロジェクト概要と担当領域
ハウスメーカーと住宅を購入した顧客がコミュニケーションを取るアプリ。
顧客が使用するWebアプリと大手ハウスメーカーが使用するWebアプリ、それぞれのWeb画面に提供するAPIの開発を担当。

#### 役割   
- Webフロントエンドエンジニア
- バックエンドエンジニア

#### 担当工程
- 要件定義
- 設計
- 実装
- テスト

#### 使用技術  
- Ruby on Rails
- React
  - react-pdf
  - react-table

#### 担当業務  
- 複数画面のAPI繋ぎ込み(Webフロント)
- react-pdfを使用したWebフロントでのPDF生成(Webフロント)
- 複数ファイルのアップロード機能(Webフロント/バックエンド)
- react-tableを使用した週次カレンダー機能の作成(Webフロント/バックエンド)  
- 各区分ごとにソートを行う処理(バックエンド)
- パフォーマンスの最適化(バックエンド)

### 大手メガネメーカー店舗向けサービス(2019/6 ~ 2020/9)

#### プロジェクト概要と担当領域
メガネの販促アプリ。購入後は保険証をアプリで管理することが出来る。
実際にメガネを購入するユーザーが使用するAndroidアプリと、ネイティブアプリに提供するAPIサーバーを作成。

#### 役割
- バックエンドエンジニア
- Androidエンジニア

#### 担当工程
- 設計
- 実装
- テスト

#### 使用技術
- Ruby
  - Ruby on Rails
- Java(Android)

#### 担当業務
- バックエンド
  - 友達招待機能
  - Railsアップグレード(4.2->5.2)
  - GMOPaymentを使用した決済機能のベース実装
- Android
  - 楽天Pay、LINEPayの決済機能
  - クレジットカードのカメラ読み取り機能

</details>

</details>

### 株式会社taliki (2018年6月 ~ 2019年3月)
<details>

インターンとして参画、インフラエンジニアを担当しました。

#### プロジェクト概要と担当領域
SNS上で応援を集められるサービス"[ちあちあ](https://prtimes.jp/main/html/rd/p/000000003.000036295.html)"のインフラ構築を担当しました。

#### 役割
- インフラエンジニア

#### 使用技術
- AWS
  - EC2
  - ELB
  - Route53
- Nginx
- PostgreSQL

#### 担当工程
- 実装(インフラ構築)

#### 担当業務
- EC2上にDjango実行環境の構築
  - DB: PostgreSQL
  - Webサーバー: Nginx
- お名前.comからRoute53へのドメイン移管
- お名前.comからRoute53へDNSを変更

</details>

### 株式会社Hatty&Co. (2018年6月 ~ 2018年10月)
<details>

1人目のエンジニアとして参画、CTOを担当しました。  

#### プロジェクト概要と担当領域
大学のサークルを経由してチャットできるマッチングアプリ、"Camel"の構築を担当しました。  
資金調達や開発が難航したため、リリースには至りませんでした。

#### 役割
- エンジニア
- CTO

#### 使用技術
- Ruby on Rails
- AWS
  - EC2
  - ELB
  - Route53
  - RDS
- Nginx
- MySQL

#### 担当工程
- 要件定義
- 設計
- 実装
- テスト

#### 担当業務
- 機能一覧の作成
- API設計
- DB設計
- ユーザー、グループ、チャットルームのCRUD等、主要な機能を実装

</details>

## 個人の活動
### 登壇
- What is Soft Memory Limit?@[Go 1.19 Release Party](https://gocon.connpass.com/event/253355)
  - [登壇資料](https://speakerdeck.com/yagipy/what-is-soft-memory-limit)
  - [ブログ記事](https://blog.yagipy.me/go119party)
- Building markdown editor using Rust’s parser@[JS Conf JP 2021](https://jsconf.jp/2021)
  - [登壇資料](https://speakerdeck.com/yagipy/building-markdown-editor-using-rusts-parser)
  - [ブログ記事](https://blog.yagipy.me/jsconfjp-2021)
- OSSに貢献した話と社内での取り組みについて@[技育祭2021](https://talent.supporterz.jp/geeksai/2021)
  - [登壇資料](https://speakerdeck.com/yagipy/ossnigong-xian-sitahua-toshe-nei-tefalsequ-rizu-minituite)
  - [ブログ記事](https://blog.yagipy.me/geeksai-lt)
- 簡易的な推薦機能を実装する@社内LT
  - [登壇資料](https://speakerdeck.com/yagipy/jian-yi-de-natui-jian-ji-neng-woshi-zhuang-suru)
- Git/GitHub oneliner command@社内LT
  - [登壇資料](https://speakerdeck.com/yagipy/github-oneliner-command)

### OSS
Owner - 私自身が作成し運用しているOSSになります  
Maintainer - リポジトリに対するWrite権限を持っているOSSになります  
Contributor - コントリビュートしたことのあるOSSになります(ここでは私自身が作成したPRがマージされたことのあるOSSに限定しています)

- Owner - [maintidx](https://github.com/yagipy/maintidx)
  - maintainability indexを計測するために作成した静的解析ツールです 
  - GitHub Starを60以上獲得しています
  - 詳しくは[こちら](https://blog.yagipy.me/analyze-maintainability-index)
- Owner - [chameleon editor](https://cameleon-editor.netlify.app/)
  - HTML、スライド、マインドマップに描画可能なマークダウンエディタです 
  - マークダウンパーサーはRustとwasmを使用しています
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

### OSS以外の個人プロジェクト
- [runlive](https://runlive.netlify.app/)
  - 事業化を目指しており、現在ソースコードはプライベートで開発しています 
  - 複数言語が実行可能なプレイグラウンドです
    - 現在はPythonのみサポートしています
  - WebRTCを使用したリアルタイムに変更が反映されるコラボレーション機能、wasmを使用したWeb完結でのソースコード実行機能、ソースコードのシェア機能があります 
  - 今後はデプロイ機能やアカウント管理機能も追加する予定です

### コミュニティ
- トレーニー - [SecHack365](https://sechack365.nict.go.jp)
  - [SecHack365](https://sechack365.nict.go.jp)という"セキュリティイノベーター"人材育成のために、NICTが主催しているプログラムに参加しています
  - 2022年度のトレーニーとして参加しています
  - RustとLLVMを使用して、プログラミング言語を作成しています
    - 所有権付き参照カウントという、特徴的なメモリ管理機能を実装しています
- Staff - [Go Conference](https://gocon.jp)
  - [2022 Spring](https://gocon.jp/2022spring/) から運営のお手伝いをしています
