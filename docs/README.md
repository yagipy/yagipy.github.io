お仕事のご依頼は[TwitterのDM](https://twitter.com/messages/compose?recipient_id=812979422554779648) 、もしくは yo@yagipy.me までお願いします。

## あなたは誰
八木橋拓之(Hiroyuki Yagihashi)です。  
特にGo/Node.jsを使用したAPIサーバーや開発ツールの開発、パブリッククラウド(AWS, GCP)を用いたインフラ/DevOps構築を得意としています。  
Reactを使用したWebクライアントの開発、Go/Node.jsの他にRailsを用いたAPIサーバー開発、Androidアプリ開発も対応可能です。  
最近の業務内容としては、基本設計(要件が技術的に可能かどうかの検証、外部APIとの連携フロー作成)、詳細設計(DB設計、API設計)、ベースコードの作成、会社単位で導入事例のない技術の検証と実装を行い、他の部分は困ったら適宜サポートするというのがメインになります。  
サポートは主にレビューやペアプロ等を通して、設計意図の共有やメンバーが設計に沿った実装を行えるようにしています。

## 興味
より多くのユーザーや開発者が使用しているサービスやライブラリを書くことに興味があります。  
担当領域の広さに比例してやる気が高まる傾向があります。幅広い領域を担当することで、より全体最適な意思決定を行える確率が高まると考えています。  

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
### からくり株式会社 (期間 2019年4月 ~ 在職中)
<details>

2019年4月に新卒入社。  
テックリード(Webフロントエンド/バックエンド)、教育グループリーダー、ソフトウェアエンジニアを担当。

#### テックリードとして
<details>

Webフロントエンド/バックエンドに関する意思決定や設計、技術選定、レビューを担当。

- open apiやGraphQL、gRPCを使用したスキーマ駆動開発の導入
  - GraphQL(graphql-ruby, apollo-client)の導入
  - gRPCの導入(ruby, golangのサービス間通信、grpc-gatewayを使用したHTTP通信の提供)
- terraformを使用したIaCの導入
- Next.jsの導入
- Recoilの導入
- ECS on Fargateを使用した本番環境のDocker化
  - 開発環境でのみ使用されていたDockerを本番環境に導入
</details>

#### 教育グループリーダーとして
<details>

教育グループには各プラットフォームのテックリードが参加しており、会社レベルでの教育に関する施策の立案や実行を担当。  
主に行った施策は下記になります。

- KPIの立案・作成・運用
- コンピテンシーマトリクスの立案・作成・運用
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

- 工事現場での無傷事故報告アプリ(2021/06~現在)

今まで会社で使用していたサーバーサイドの言語はRubyとTypeScriptでしたが、この案件で初めてGoを導入しました。  
ただ、社内でGoを書ける人が少なかったので、アプリケーションレイヤをマイクロサービス化し部分的かつ段階的にGoを導入していきました。  
具体的にはゲートウェイサーバーはGo、他のサーバーは書けるメンバーが多く社内に知見がたまっているという点でRubyを採用しました。  
サービス間の通信はgRPCを使用しています。  
grpc-gatewayを使用して各クライアント(Webフロント、iOS、Android)にはREST APIを提供する形を取りました。  
このことによってgRPCを導入した影響を最小限にしつつ、スキーマファーストな開発を導入することに成功しました。  
インフラについても、今まではAWS EC2にAnsibleでプロビジョニングする形でしたが、サーバーレスかつコンテナ化を実現したいという理由で、ECS on Fargate上に構築しました。  
サーバーレスかつコンテナ化することで、インフラ管理コストの大幅な軽減、AutoScalingの容易化及び高速化、ベンダーロックインの回避を実現できました。

- 認証認可基盤システム(2020/10~現在)

管理画面とAPI開発がメインでした。(APIは15本あります。)  
管理画面がセキュリテイ要件を満たすためにEC2ホスティング、API側はAPI Gateway + Lambdaのマイクロサービス構成です。DBはRDSです。(コネクション管理はRDS Proxyを使用しています。)  
最初は取引会社さんの方でもAWSWebコンソールでインフラを変更する可能性があるということだったので、API全体の管理ライブラリは導入せず、デプロイや環境変数の切り替えはシェルスクリプトを使用していました。  
Serverless FrameworkやAWS SAMはインフラの設定に意図しない変更が出てしまうことを懸念して導入を見送っていました。  
ですが、取引会社さんの方で変更する部分が大体分かってきたというのもあり、大きな機能追加開発が入るタイミングでServerless Frameworkを導入しました。  
導入によって基盤全体の見通しが良くなっただけではなく、属人化の排除、インフラ設定の共通化、テスト環境と開発環境での実行が容易に出来るようになりました。   

- 大手ハウスメーカー顧客管理サービス(2020/2 ~ 2020/6)

Web フロント(React)/バックエンド(Rails)を担当しました。  
主に React を使用して Web クライアントの実装を行っていました。  
react-pdf を使用したクライアント側での PDF 生成、複数ファイルのアップロード機能、react-table を使用した週次カレンダー機能等を実装しました。  
APIサーバーについてもいくつかAPIを実装しており、各区分ごとにソートを行う処理やパフォーマンスの最適化などを行いました。

- 大手メガネメーカー店舗向けサービス(2020/1 ~ 2020/9)

バックエンド(Rails)/Android(Java)をメインに開発してました。  
Railsアップグレード(4.2->5.2)、総合決済サービスを使用した決済機能のベース実装等を担当しました。
Android は楽天Pay、LINEPayの決済機能、クレジットカードのカメラ読み取り機能の実装を担当しました。

- 宿泊者管理サービス(2020/6 ~ 2020/9)

Webフロント/バックのリードとして、技術選定からアーキテクト、実装まで一通りの工程を担当しました。
Rails を使用した GraphQL サーバー構築、Next.js を使用した Web クライアント構築、terraform でのインフラ構築を担当しました。

</details>
</details>

### 株式会社taliki (期間 2018年6月 ~ 2019年3月)
<details>

インターンとして参画。  
SNS上で応援を集められるサービス「ちあちあ」のインフラ構築を担当。  
https://prtimes.jp/main/html/rd/p/000000003.000036295.html

#### 使用技術
- AWS
  - EC2
  - ELB
  - Route53
  - etc...
- Nginx
- PostgreSQL

#### 職務内容
- EC2上にDjango実行環境の構築
  - DB: PostgreSQL
  - Webサーバー: Nginx
- お名前.comからRoute53へのドメイン移管
- お名前.comからRoute53へDNSを変更

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
- Team member - [golangci-lint](https://github.com/golangci/golangci-lint)
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
