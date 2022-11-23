<!--
TODO
- テックリードとしてプロジェクトに参加しているが、各プロジェクトではリードエンジニアになっている
-->
このページは @yagipy の職務経歴を紹介するページです。  
最終更新日: 2022/10/16

## 目次
- 基本情報
- 自己紹介
  - 理想像と現在の行動
  - 興味
- 職務経歴
  - からくり株式会社 (2019年4月 ~ 在職中)
  - 株式会社taliki (2018年6月 ~ 2019年3月)
  - 株式会社Hatty&Co. (2018年6月 ~ 2018年10月)
- 個人の活動
  - 登壇
  - OSS
  - OSS以外の個人プロジェクト
  - コミュニティ
- 各種リンク
<!--
- 興味
-->

## 基本情報
<table>
  <tr>
    <td>氏名</td>
    <td>八木橋 拓之</td>
  </tr>
  <tr>
    <td>氏名(フリガナ)</td>
    <td>ヤギハシ ヒロユキ</td>
  </tr>
  <tr>
    <td>生年月日</td>
    <td>1998/10/19</td>
  </tr>
  <tr>
    <td>性別</td>
    <td>男</td>
  </tr>
  <tr>
    <td>連絡先</td>
    <td>yo@yagipy.me</td>
  </tr>
</table>

## 自己紹介
八木橋拓之(Hiroyuki YAGIHASHI)です。  
バックエンドエンジニアとして、主にGo/Node.jsを使用したAPIサーバーやライブラリの開発、AWSを用いたインフラ構築を得意としています。  
Reactを使用したWebクライアントの開発、Go/Node.jsの他にRailsを用いたAPIサーバー開発、Androidアプリ開発も実務経験があります。  
直近の業務内容は、見積作成、設計(DB設計、API設計、技術選定)、ベースコードの作成、会社単位で導入事例のない技術の検証と実装を行いつつ、他メンバーのサポートをするというのがメインになります。  
サポートは主にレビューやペアプロ等を通して、設計意図の共有やメンバーが設計に沿った実装を行えるようにしています。

### 理想像と現在の行動
2025年までには**大規模OSSと複雑なシステムの開発をリードする存在になり、様々な技術的課題を解決する**という理想像があります。  
前までは、**必要十分に品質の高いプロダクトを1人で作れるようになる**という理想像がありました。  
様々なプロジェクトで設計や技術選定から実装やテストまでを任せていただき、その理想像はほぼ達成できたと考えています。  
ですが、様々な技術の比較検討を行なっていく中で、あくまで技術の利用者でしかないという感覚と、技術的課題によってできないことがあるという現実の2点を強く感じるようになりました。  
今は利用者としてだけではなく提供者として様々な技術に関わっていきたいと考えています。  
そして、様々な技術に存在している技術的課題を解決していくことで、作りたいプロダクトが技術的課題によって作れない、ということをなくしていきたいと考えています。

現在の行動としては、様々なOSSを作成したり大型OSSにコントリビュートをしています。  
どういったOSSに力を入れていくかはまだ決定できていません。  
あと複雑なシステムを高品質に保つためには分散システムの知識が必要だと感じ、[データ指向アプリケーションデザイン](https://www.oreilly.co.jp/books/9784873118703)などの本を読んでいます。

### 興味
分散システム、プログラミング言語(主にメモリ管理)、Rustに興味があります。

分散システムは可用性、性能、拡張性、運用保守性、セキュリティ等が高いレベルで満たされているシステムを設計するのに必須な知識だと考えていて、学習を続けています。  
現在は[データ指向アプリケーションデザイン](https://www.oreilly.co.jp/books/9784873118703)や[Azureアーキテクチャセンター](https://learn.microsoft.com/ja-jp/azure/architecture)などを読んで学習しています。  

プログラミング言語は普段書いている中でどういった仕組みで動いているのか気になり、学習を続けています。  
[ガベージコレクション](https://www.shoeisha.co.jp/book/detail/9784798134208)を読んだり、[Althea](https://github.com/yagipy/althea)という言語処理系を自作することで学習をしています。  
自作の言語処理系ではバックエンドにLLVMを使用しているため、LLVM IRはある程度読むことができます。  
メモリ管理にも興味があり、自作の言語処理系に独自のGCアルゴリズムの実装を進めています。  
マークスイープ(コンカレント含む)や参照カウンタなどの基本的なGCアルゴリズムの仕組みと特徴は理解しているつもりですが、実際の言語処理系に実装するのはそれなりに時間がかかる(大枠の方針を立てて実装は進められる)、くらいの知識です。  
今作っている言語処理系がある程度まで動作した後は自作CPUを作成し、その後OSやDBMSも自作していきたいと考えています。  

Rustは所有権やライフタイムを使用することでメモリ安全でNoGCを実現していたり、nullを排除してOptionを導入することでnull ptr derefをコンパイル時に検知できたり、よく考えられている機能が多く勉強になるため学習をしています。  
他にもResult型やデフォルトで変数が不変など、細かい部分にも気が利いていてとても良いと思っています。  
先ほどのAltheaという自作プログラミング言語や、個人開発のAPIサーバーを作成する際に使用しています。  
[the book](https://doc.rust-jp.rs/book-ja)も時間がある時につまみ読みをしています。

## 職務経歴
### からくり株式会社 (2019年4月 ~ 在職中)
2019年4月に新卒入社しました。  
テックリード(Webフロントエンド/バックエンド)、教育グループリーダー、ソフトウェアエンジニアを担当しています。

#### Webフロントエンド/バックエンドのテックリード (2021年4月 ~ 在職中)
Webフロントエンド/バックエンドに関する見積作成、設計(DB設計、API設計、技術選定)、ベースコードの作成、会社単位で導入事例のない技術の検証と実装を行いつつ、他メンバーのサポートをするというのがメインの業務になります。    
ただ、テックリード業務のための工数が毎月あるわけではなく、必要なタイミングで(新規開発立ち上げの際や新しい技術を検証/導入する際など)工数をもらい、実際にプロジェクトに参画する形で業務を行なっています。   
主な実績は**開発プロジェクト一覧**の**利用技術や技術選定に関する思考と行動**の項目に書いています。

#### 教育グループリーダー (2020年9月 ~ 在職中)
教育グループでは、会社レベルでの教育に関する施策の立案や実行を担当しました。(メンバー数最大4名)  
教育効果を定量的に測定するために、エンジニア評価制度に関しても作成しました。  
施策の立案や実行の過程で、「学習する組織」や「リファクタリング•ウェットウェア」、「成人発達理論による能力の成長」という本を読み、体系的な能力開発に関する知識を得ることができました。  
主に行った施策は下記になります。

- KGI/KPIの立案・作成・運用
- エンジニア評価制度(コンピテンシーマトリクス)の立案・作成・運用
- エンジニアメンターシップ制度の立案・作成・実施・運用
- 研修制度のプラッシュアップ
- テックリードによる塾形式の勉強会の立案・実施
- ライブラリ/設計比較検討会の立案・実施

#### 開発プロジェクト一覧
抜粋しています。  
リードエンジニアを担当したプロジェクトのみ、**利用技術や技術選定に関する思考と行動**という項目があります。  

プロジェクトの網羅性は下記ブログ記事の方が高いですが、このページの方が各プロジェクトをより詳細に書いています。  
[2021年の詳細](https://blog.yagipy.me/2021-in-review)  
[2020年の詳細](https://blog.yagipy.me/2020-in-review)

### オンライン診療アプリ
<table>
  <tr>
    <td>参画期間</td>
    <td>2021/11~現在</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>要件定義、設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      Webフロントエンド/バックエンドのリードエンジニア<br />
      Webフロントエンド/バックエンドのプロジェクトマネジメント(メンバー数最大6名)
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      フロントエンド: TypeScript、React、vite、Chakra UI<br />
      バックエンド: Go、gqlgen、ent<br />
      インフラ: Terraform、AWS、ECS、Fargate、SNS、SES、Aurora(MySQL互換)、CloudFront、Route53、ALB<br />
      その他: GitHub Actions、GMOPayment、Twilio、OMRON connect Cloud
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>

オンライン診療や医師とのチャットを行うことができるアプリです。  
患者用のWebアプリと医療従事者用のWebアプリ、システム管理者用のWebアプリ、各Webアプリとネイティブアプリに提供するAPIサーバー、インフラ構築を担当しました。
</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

- 設計(DB設計、API設計、技術選定)
- gqlgen、entを使用したベースコードの構築
- Vite、Chakra UI、Graphql Code Generatorを使用したベースコードの構築
  - Graphql Code Generatorを使用したAPI呼び出し処理(hooks)及び型定義の自動生成
- GraphQL Subscription、Redis Pub/Sub、goroutineを使用したリアルタイムチャット機能の検証及び実装
- Twilioを使用したビデオ通話機能の実装(API側のみ)
- GMOPaymentを使用した定期課金機能の実装
- OMRON connect Cloudを使用した体温計の連携機能の実装

</details>

<details>
<summary style="display: list-item">利用技術や技術選定に関する思考と行動</summary>

大きく3つのチャレンジを行いました。
- Goの全面的な導入
- GraphQLによるスキーマ駆動開発の導入
- Project-based monorepoの導入

---

#### Goの全面的な導入
##### 課題
工事現場での無傷事故報告アプリで部分的なGoの導入を行い、Rubyを使用した際の課題が解決され、かつGoを導入することのメリットを確認できました。  
今回のプロジェクトは大規模だったこともあり、全面的に導入することでGoのメリットをより享受できると考えました。  
ですが、Goを全面的に導入する際の課題として、**プロジェクト参加者に学習コストが発生する**ことが挙げられました。

##### 取り組み、工夫点
課題の対応として、まずは導入の背景や学習コストが発生することをプロジェクト参加予定のメンバーに伝え、合意形成を行いました。  
その後、学習コストを最小限にするために、下記を行いました。
- プロジェクト参加時に必要となるスキルセットを明確にする
- 上記スキルセットを習得するためのタスク一覧及び教材一覧を作成する
- 勉強会を企画し、その勉強会の中で上記タスクや教材を進める
  - 一定期間内で毎週行いました

##### 成果
上記取り組みによって、下記のような成果が得られました。
- プロジェクト参加時に必要となるスキルセットが明確であるため、必要なスキルセットのみを集中して学習することができました
- タスク一覧及び教材一覧を作成することで、タスクの洗い出しや教材の選定にかかる時間を省くと共に、案件参画後も一定の前提知識を元にコミュニケーションが取れるようになりました
- 勉強会を企画することで、定期的に学習する習慣を作れたことに加えて、それぞれの知識レベルを把握することで案件参画後のチケットの割り振りを効率よく行うことができました

---

#### GraphQLによるスキーマ駆動開発の導入
##### 課題
GraphQLによるスキーマ駆動開発を導入することによって、工事現場での無傷事故報告アプリで発生した**レスポンスを過度に共通化したことによる無駄なプロパティの発生**という課題の解決を試みました。

課題についての補足ですが、工事現場での無傷事故報告アプリでは大きく2つの方針でレスポンスを決めていました。

```
1.原則、レスポンスは対象entityの全てのプロパティを返す
  - セキュリティ上問題がある場合等は除く
2.子のentityが必要な場合は、リクエストで指定する
  - [Stripeのexpand](https://stripe.com/docs/expand)のような仕組み
  - 1に従い、子のentityは全てのプロパティを返す
```

上記の方針は、画面の表示要素を変えるたびにAPI側のコードを修正しなくても良いようにするために決めたものでした。  
ですが、モバイルの開発者から、**使用しないプロパティを返さないで欲しい**という要望がありました。

##### 取り組み、工夫点
上記課題を解決するためには、画面の表示要素を変えるたびにAPI側のコードを修正しなくても良いという部分は維持しつつ、特定のプロパティのみを返すようにする必要があると考えました。  
そのためには、クライアント側でプロパティを指定できるようにすることが必要だと判断しました。

クライアント側でプロパティを指定できるようにする方法として、2つの方法が考えられました。
- GraphQLを導入する
- RESTに[Stripeのexpand](https://stripe.com/docs/expand)と[Google CloudのAPI設計ガイドで紹介されているfields](https://cloud.google.com/apis/design/design_patterns?hl=ja#partial_response)のような仕組みを導入する

下記の理由からGraphQLを導入しました。
- expandやfieldsの仕組みを両方とも実装すると、リクエストパラメータが複雑になる可能性があった
- RESTはexpandやfieldsの仕組みを実装する必要があるが、GraphQLはライブラリ側で実装されているため、リクエストパラメータという点においては実装コストが低く抑えられる
- GraphQLは採用実績があり(宿泊者管理サービス)、問題が解決されることが明らかであった

##### 成果
上記の取り組みによって、クライアント側でプロパティを指定できるようになり、最初にあげた**レスポンスを過度に共通化したことによる無駄なプロパティの発生**の解決に成功しました。  
かつ、工事現場での無傷事故報告アプリでgRPCを導入した際と同じく、スキーマ駆動開発によって各クライアントとの意思疎通が容易になり、ドキュメンテーションにかかる時間も削減できました。

---

#### Project-based monorepoの導入
こちらはプロジェクト立ち上げ初期からではなく、途中から導入しました。

##### 課題
初期はAPIサーバー、Webクライアント、GraphQLスキーマの3つリポジトリに分け、APIサーバーとWebクライアントでGraphQLスキーマのリポジトリをsubmoduleとして参照していました。  
この構成で1ヶ月程度運用してみたところ、下記の問題が発生しました。
- GraphQLスキーマの変更を行うと、APIサーバーとWebクライアントの2つのリポジトリで変更を取り込む必要がある
  - プロジェクトの新規開発フェーズでは、GraphQLスキーマの変更が頻繁に発生するため、この作業が大きなコストになっていました
- entの機能で自動生成しているGraphQLスキーマが最新かどうか担保できない
  - GraphQLスキーマをマージする際は、毎回entで変更が入っていないかを確認する必要があり、途中で変更が入るとその度にPRを出す必要がありました
- 生成コードとスキーマの整合性が取りづらい
  - gqlgenのgenerateが失敗しているのに気づかず、GraphQLスキーマをマージしてしまうことが何度かありました
- ソースコードとPRの管理が煩雑

##### 取り組み、工夫点
上記の問題を解決するためにAPIサーバー、Webクライアント、GraphQLスキーマの3リポジトリを1つのリポジトリに統合しました。  
かつ、GitHub Actionsでgenerateのチェックを行うようにし、generateされていなかった場合はマージをブロックするようにしました。

##### 成果
上記の取り組みによって、下記のように問題が解決されました。
- GraphQLスキーマ変更時の作業コストが大幅に削減された
- entの機能で自動生成しているGraphQLスキーマが最新かどうか担保できるようになった
  - 途中でentに変更が入っても、その度にPRを出す必要がなくなった
- 生成コードとスキーマの整合性をCIによって自動で担保できるようになった
- ソースコードとPRの管理が容易になった

</details>

### 工事現場での無傷事故報告アプリ
<table>
  <tr>
    <td>参画期間</td>
    <td>2021/06~現在</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>要件定義、設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      Webフロントエンド/バックエンドのリードエンジニア<br />
      Webフロントエンド/バックエンドのプロジェクトマネジメント(メンバー数最大5名)
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      フロントエンド: TypeScript、React、Next.js、Recoil、TailwindCSS<br />
      バックエンド: gRPC、Go、grpc-gateway、Ruby、guard<br />
      インフラ: AWS、ECS、Fargate、SNS、Aurora(MySQL互換)、CloudFront、Route53、ALB<br />
      その他: GitHub Actions
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>

工事現場で無傷事故(ヒヤリハット)が発生した際に報告を行うアプリです。  
報告された内容を確認する管理者用のWeb画面、ネイティブアプリと管理者用Web画面に提供するAPI開発を担当しました。

</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

- 設計(DB設計、API設計、技術選定)
- grpc-gateway、grpc_tools_ruby_protocを使用したgRPCサーバーのベースコード構築(Ruby、Go)
- Next.js、TailwindCSS、Recoilを使用したベースコードの構築
- Amazon ECS、AWS Fargateを使用したインフラの構築
- GitHub Actionsを使用した自動デプロイフローの構築
- guardを使用したRubyサーバーのオートリロード
- APIのページネーションとフィルタリング機能の共通モジュールの実装

</details>

<details>
<summary style="display: list-item">利用技術や技術選定に関する思考と行動</summary>
 
大きく3つのチャレンジを行いました。
- Goの部分的な導入
- gRPCを使用したスキーマ駆動開発の導入
- Amazon ECSとAWS Fargateの導入

---

#### Goの部分的な導入
今まで会社がメインで使用していたサーバーサイドの言語はRubyでしたが、この案件で初めてGoを導入しました。

##### 課題
この意思決定には、Rubyを使用した際の課題が関係しています。  
私が考えている、Rubyを使用した際の課題は下記になります。
- 動的型付け言語であり、実行しないとエラーの検出が難しい
- 実行速度が遅い
  - 大手ハウスメーカー顧客管理サービスで問題になっていました
- コミュニティが衰退してきていると感じる
  - [TIOBE index](https://www.tiobe.com/tiobe-index/ruby)や[State of the Octoverse](https://octoverse.github.com)等の情報から衰退していると判断しました
  - 技術的な部分ではなく、多くの人が使っているから良いという訳ではないものの、OSSにおいてコミュニティは重要だと考えています
    - 特にRuby/Ruby on Railsは日本のコミュニティが盛んで、そこに大きな価値があると考えているため、コミュニティの衰退は痛手だと判断しました

##### 取り組み、工夫点
上記課題から、採用する言語は静的型付け言語で、実行速度が早く、コミュニティが盛んである必要があり、いくつか候補がある中からGoを選択しました。(Goの他にKotlinとTypeScriptを検討しました)  
Goを選択した理由としては下記になります。
- 静的型付け言語であり、コンパイル時にエラーを検出できる
- 実行速度が早い
- コミュニティが盛んである
- 言語仕様がシンプルであり、動的型付け言語を扱っていた人でも比較的容易に習得できる
  - Rubyを使っている人が多いのと、大規模なアプリになる可能性が高くプロジェクトに参加する人数が多くなることを考えると、習得難易度は重要でした
- 依存先を比較的少なくできる
  - 大手メガネメーカー店舗向けサービスで依存関係の更新を行う際に、依存先の数が多く更新にコストがかかっており、かつ一部は更新の際にエラーが発生し古いバージョンで固定した経験がありました
  - そのため、依存先を少なくできることは魅力的でした

ただ、社内でGoを書ける人が少なかったので、アプリケーションレイヤをマイクロサービス化し、部分的かつ段階的にGoを導入しました。  
具体的にはgatewayサーバーはGo、他のサーバーは書けるメンバーが多く社内に知見がたまっているという点でRubyを採用しました。  
サーバー間の通信はgRPCを使用しました。

##### 成果
上記取り組みによって、下記のような成果を得ることができました。
- コンパイル時にエラーを検出できるようになった
- 実行速度が早くなった
- コミュニティが盛んであるため、コミュニティの知見をより活用できるようになった
- 言語仕様がシンプルであるため、動的型付け言語を扱っていた人でも比較的容易に習得できた
  - 他の静的型付け言語を導入していないため比較はできませんが、言語仕様の把握や習得に大きく困ることはなかったため、この判断としています
- 依存先を比較的少なくできた

---

#### Protocol BuffersとOpenAPIを使用したスキーマ駆動開発の導入 
##### 課題
APIのインターフェースはフロントエンドとバックエンドの間で共通の認識を持つ必要があります。  
今までのプロジェクトでは、APIのインターフェースはドキュメントか口頭によって共有されており、下記のような課題がありました。
- 必要な情報が足りない等の不備が発生する可能性がある
- APIの数が多くなると管理が難しくなり、実装とドキュメントの内容が乖離してしまう
  - 口頭も上記と同様に、伝えたタイミングから変更があった場合は、内容が乖離してしまう
- 人によって書き方や伝え方にばらつきがあり、認識を合わせるのに時間がかかる

##### 取り組み、工夫点
上記課題を解決するために、Protocol BuffersでAPIインターフェースを定義し、Protocol BuffersからOpenAPIを自動生成するようなフローでスキーマ駆動開発を実現しました。  
なぜそのような構成にしたのかを書いていきます。  
まず最初に、スキーマ駆動開発を導入する際の選択肢として一般的かつ実績が豊富なのは下記2つであると考えました。
- OpenAPI
- Protocol Buffers

最初はgRPCで十分にサポートされていない言語やクライアントを考慮しOpenAPIのみを使用することも考えましたが、下記のような理由からProtocol Buffersを書き、OpenAPIを自動生成する形を採用しました。
- エンジニアが書くIDLを統一したかったため
  - gatewayサーバーと他のサーバー間の通信はgRPCを使用していたため、既にProtocol BuffersをIDLとして使用していました
  - なぜサーバー間通信にgRPCを使用しているかは下記2つが理由になります
    - プライベートなAPIなので、標準的なHTTP技術のみで叩ける必要がないため
    - URLパスやHTTPメソッド等を決める必要がなく、より必要なことのみに集中できるため(メソッドライクに書けるため)
- grpc-gatewayを使用することで、Protocol Buffersでインターフェースを書きつつ、各クライアントにRESTful APIを提供することが容易に可能だったため
  - このことによって、記述するIDLをProtocol Buffersに統一しながらも、gRPCで十分にサポートされていない言語やクライアント向けにRESTful APIを提供することができました
  - grpc-gatewayを使用することで、提供しているRESTful APIに従ったOpenAPIを自動生成することも可能です

##### 成果
上記取り組みによって、下記のような成果が得られました。
- スキーマからソースコードを自動生成できるようになりました
  - 型不一致エラーが発生しない最低限必要な情報が揃っていることが保証される
  - スキーマ(ドキュメント)と実装が乖離しない
- IDLは人による記述のばらつきが少なくなるため、認識を合わせやすくなりました
- 各クライアントとの意思疎通が容易になりました
- ドキュメンテーションにかかる時間を削減できました

---

#### Amazon ECSとAWS Fargateの導入
Amazon ECSとAWS Fargateは、サーバーレスかつコンテナ化を実現するために導入を行いましたので、ここではなぜサーバーレスかつコンテナ化を実現したかったのかについて書きます。

##### 課題
今まではAWS EC2にAnsibleでプロビジョニングする形でしたが、下記のような課題がありました。
- 開発環境、STG環境、PRD環境でそれぞれ動作環境が違う
  - 動作環境が異なるため、他環境で再現しない不具合が発生しやすい
  - Ansible自体はVagrantで仮想環境を立てて動作確認をしていたが、Ansibleの動作確認のために仮想環境を立てるのはコストに見合わないと考えていました
    - 実際にその上でアプリを動かすと同じ動作環境で実行できますが、計算リソース的に無駄が多いと考えていました
- EC2関連の管理作業が後回しにされていた
  - OSのバージョンアップなど

##### 取り組み、工夫点
上記の問題を、サーバーレスかつコンテナ化をすることで解決したいと考えました。  
パブリッククラウドはAWSを使用していたため、AWSで提供されているサービスであるAmazon ECSとAWS Fargateを採用しました。  
コントロールプレーンはEKSでも可能でしたが、EKSはECSに比べて学習コストおよび運用コストが高いと考えており、今後何かしらの課題が発生した際はEKSにする可能性はあるが、問題が発生するまではECSで良いと判断しました。

##### 成果
サーバーレスかつコンテナ化することで、下記のような成果が得られました。
- コンテナ化することで、開発環境、STG環境、PRD環境で動作環境を統一することができました
- サーバーレス化することで、EC2関連の管理作業が不要になりました
- インフラ構築時のコストが削減できました
- AutoScalingの容易化及び高速化が可能になりました

</details>

### 認証認可基盤システム
<table>
  <tr>
    <td>参画期間</td>
    <td>2020/10~現在</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>要件定義、設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      Webフロントエンド/バックエンドのリードエンジニア<br />
      Webフロントエンド/バックエンドのプロジェクトマネジメント(メンバー数最大2名)
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      フロントエンド: TypeScript、React、Next.js、Recoil、TailwindCSS<br />
      バックエンド: JavaScript、TypeScript、prisma、ldapjs、samba-client、sequelize、Serverless Framework<br />
      インフラ: AWS、Lambda、API Gateway、EC2、RDS、RDS Proxy<br />
      その他: GitHub Actions
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>
 
社員が使うアプリの認証が各アプリのサーバーで実装しており、情報が散在しているという課題がありました。  
その情報を集約することを目的に、認証認可基盤を作成しました。  
管理者が使用するWebアプリとAPI開発を担当しました。

</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

- 技術選定
- Serverless Frameworkを使用したベースコードの構築
- Next.js、Recoil、TailwindCSSを使用したベースコードの構築
- LDAP認証の実装
  - ディレクトリサービスはActive Directoryを使用
- Sambaサーバーへのファイルアップロード実装
  - Lambda上でAmazonLinux2のネイティブバイナリパッケージ(samba-client)を使用することで実現
- CSVをstreamにして読み込みつつDBにインサートするバッチ処理の実装
- ldapjsを使用したパスワード変更機能の実装

</details>

<details>
<summary style="display: list-item">利用技術や技術選定に関する思考と行動</summary>

インフラ構成や言語については、お客さんの方から要望があったため、要望に答える形で実装しました。  
APIはAPI Gateway + Lambdaの構成になっています。  
DBはMySQL互換のRDSを使用しています。(コネクション管理はRDS Proxyを使用しています。)  
管理画面は"アクセスをプライベートネットワークに閉じたい"という要件があったため、会社でよく使っていたS3の静的Webサイトホスティングを使用して、プライベートIPのみを設定できないか調査を行いました。  
上記を調査しているタイミングでAWS PrivateLink for Amazon S3の一般提供が開始され、これで可能になると考えていたのですが、静的WebサイトホスティングはPrivateLinkに対応していないことがわかりました。  
最終的にはEC2でホスティング(Nginxを使用しています)を行いました。

最初はお客さんの方でもAWS Web コンソールでインフラを変更する可能性があるということだったので、API全体の管理ライブラリは導入せず、デプロイや環境変数の切り替えはシェルスクリプトを独自に組んで使用していました。  
Serverless FrameworkやAWS SAMはインフラの設定に意図しない変更が出てしまうことを懸念して導入しないという判断をしました。  
ですが、取引会社さんの方で変更する部分が大体分かってきたというのもあり、取引会社さんと交渉し、大きな機能追加開発が入るタイミングでServerless Frameworkを導入しました。  
導入によって基盤全体の見通しが良くなっただけではなく、属人化の排除、インフラ設定の共通化、テスト環境と開発環境での実行が容易に出来るようになりました。  
なお、上記のタイミングでJavaScriptからTypeScriptへの移行も行い、より安全に開発を行えるようになりました。

TODO: 更新する
Webアプリは新しくRecoilを導入しました。

</details>

### 宿泊者管理サービス
<table>
  <tr>
    <td>参画期間</td>
    <td>2020/6~2020/9</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>要件定義、設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      Webフロントエンド/バックエンドのリードエンジニア
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      フロントエンド: TypeScript、React、Next.js、Redux、Redux Toolkit、Redux Saga、Apollo Client<br />
      バックエンド: Ruby、Ruby on Rails、graphql-ruby、capistrano<br />
      インフラ: Terraform、AWS、EC2、RDS、ALB、S3、CloudFront<br />
      その他: CircleCI
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>
 
宿泊者の入退室を管理したり、管理者とチャットやビデオ通話を行うことが出来るアプリです。
管理者が使用するWebアプリとAPI開発を担当しました。

</details>

<details>
<summary style="display: list-item">主な担当業務</summary>
 
- graphql-rubyを使用したベースコードの構築
- Next.js、Apollo Client、Redux、Redux Toolkitを使用したベースコードの構築
- Terraformを使用したインフラ構築

</details>

<details>
<summary style="display: list-item">利用技術や技術選定に関する思考と行動</summary>
 
大きく3つのチャレンジを行いました。
- GraphQLの導入
- Next.jsの導入
- Terraformを使用したIaCの導入

GraphQLの導入ですが、大手ハウスメーカー顧客管理サービスで発生していた問題を解決することを試みました。
主に問題となっていたのは下記の3つです。
- 画面の表示要素を変えるたびに、API側のコードを修正する必要がある
- 1画面で複数のAPIを叩いており、画面描画に遅れが出ていた/フロント側で取得した値を管理しづらい
- APIが様々な画面で叩かれているため、どのレスポンスの値がどこで使われているか把握しづらく、レスポンスの値を削除しにくい

解決策として、下記の2つを候補として考えました。
- RESTに[Stripeのexpand](https://stripe.com/docs/expand)や[Google CloudのAPI設計ガイドで紹介されているfields](https://cloud.google.com/apis/design/design_patterns?hl=ja#partial_response)というリクエストパラメータを追加し、レスポンスをリクエストパラメータに応じて変更するようにする
- GraphQLを使用する

どちらでも解決可能でしたが、下記の理由によりGraphQLを採用しました。
- アプリの比較的小規模であり、挑戦的な技術選定が可能であるため
- 今後社内でGraphQLを導入する可能性を考慮し、小規模なアプリで使用することで影響範囲を最小限にしつつ社内にGraphQLの知見をためることができるため
- コアロジックを分離しておけば低コストでRESTへの切り替えが可能であると判断したため

その結果、問題が解決されただけではなく、今後の開発においてもGraphQLという選択肢を取ることが以前より容易になり、会社全体としても問題解決の幅が広がったと考えています。

TODO: Next.jsの導入の思考を書く  
TODO: Terraformを使用したIaCの導入の思考を書く

</details>

### 大手ハウスメーカー顧客管理サービス
<table>
  <tr>
    <td>参画期間</td>
    <td>2020/2~2020/6</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>要件定義、設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      Webフロントエンド/バックエンドエンジニア
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      フロントエンド: TypeScript、React、Create React App、Redux、react-pdf、react-table<br />
      バックエンド: Ruby、Ruby on Rails、capistrano<br />
      その他: GitHub Actions、CircleCI、Ansible
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>
 
ハウスメーカーと住宅を購入した顧客がコミュニケーションを取るアプリです。
顧客が使用するWebアプリと大手ハウスメーカーが使用するWebアプリ、それぞれのWeb画面に提供するAPIの開発を担当しました。

</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

- 複数画面のAPI繋ぎ込み
- react-pdfを使用したWebフロントでのPDF生成
- 複数画像のアップロード機能
- react-tableを使用した週次カレンダー機能の作成  
- 各区分ごとにソートを行う処理の実装
- 上記ソート処理のパフォーマンス最適化

</details>

### 大手メガネメーカー店舗向けサービス
<table>
  <tr>
    <td>参画期間</td>
    <td>2019/6~2020/9</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      バックエンドエンジニア
      Androidエンジニア
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      Android: Java、Android、Dagger、RxJava<br />
      バックエンド: Ruby、Ruby on Rails<br />
      その他: GitHub Actions、Circle CI、Ansible
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>

ユーザーがメガネ購入後に、保険証等の情報を管理できるアプリです。
他にもユーザーの投稿、タイムライン、販売中のメガネ一覧、友達招待などの複数機能があります。
実際にメガネを購入するユーザーが使用するAndroidアプリと、ネイティブアプリに提供するAPIの開発を担当しました。

</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

- バックエンド
  - 友達招待機能
  - Railsアップグレード(4.2->5.2)
  - GMOPaymentを使用した決済機能のベース実装
- Android
  - 楽天Pay、LINEPayの決済機能
  - クレジットカードのカメラ読み取り機能

</details>

### 株式会社taliki (2018年6月 ~ 2019年3月)

インターンとして参画、インフラエンジニアを担当しました。

#### 開発プロジェクト一覧
### ちあちあ
<table>
  <tr>
    <td>参画期間</td>
    <td>2018/6~2019/3</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>実装</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      インフラエンジニア
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      AWS、EC2、ALB、Route53、Nginx、PostgresQL
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>

SNS上で応援を集められるサービス[ちあちあ](https://prtimes.jp/main/html/rd/p/000000003.000036295.html)のインフラ構築を担当しました。
</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

- EC2上にDjango実行環境の構築
  - DB: PostgreSQL
  - Webサーバー: Nginx
- お名前.comからRoute53へのドメイン移管
- お名前.comからRoute53へDNSを変更

</details>

### 株式会社Hatty&Co. (2018年6月 ~ 2018年10月)

1人目のエンジニアとして参画、CTOを担当しました。  

#### 開発プロジェクト一覧
### Camel
<table>
  <tr>
    <td>参画期間</td>
    <td>2018/6~2018/10</td>
  </tr>
  <tr>
    <td>担当工程</td>
    <td>要件定義、設計、実装、テスト</td>
  </tr>
  <tr>
    <td>役割</td>
    <td>
      エンジニア
    </td>
  </tr>
  <tr>
    <td>主な使用技術</td>
    <td>
      Ruby、Ruby on Rails、AWS、EC2、ALB、RDS、Route53、Nginx、MySQL
    </td>
  </tr>
</table>

<details>
<summary style="display: list-item">プロジェクト概要と担当領域</summary>

大学のサークルを経由してチャットできるマッチングアプリ、Camelの構築を担当しました。  
資金調達や開発が難航したため、リリースには至りませんでした。

</details>

<details>
<summary style="display: list-item">主な担当業務</summary>

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
  - [SecHack365](https://sechack365.nict.go.jp)という、セキュリティイノベーター人材育成のためにNICTが主催しているプログラムに参加しています
  - 2022年度のトレーニーとして参加しています
  - RustとLLVMを使用して、プログラミング言語を作成しています
    - 所有権付き参照カウントという、特徴的なメモリ管理機能を実装しています
- Staff - [Go Conference](https://gocon.jp)
  - [2022 Spring](https://gocon.jp/2022spring/) から運営のお手伝いをしています

## 各種リンク
- [GitHub](https://github.com/yagipy)
- [Twitter](https://twitter.com/yagipy_)
- [Blog](https://blog.yagipy.me)
- [SpeakerDeck](https://speakerdeck.com/yagipy)
