# AWS Certified Data Analytics - Specialty

# AWS認定 データ分析 - 専門知識

# 試験範囲

|  #  | 範囲 | 出題比率 | 
| --- | --- | --- | 
|    第 1 分野  | 収集    | 18%    | 
|   第 2 分野  | ストレージとデータ管理    | 22%     | 
|  第 3 分野   | 処理    | 24%    | 
|   第 4 分野   | 分析と可視化    | 18%    | 
|   第 5 分野  | セキュリティ    | 18%    | 

# 範囲内の AWS のサービスと機能 

## 分析: 
| サービス名 | 概要 | 
| --- | --- | 
| Amazon Athena |  | 
| Amazon CloudSearch  |  | 
| Amazon EMR |  |  
| AWS Glue  |  | 
| Amazon Kinesis |  |  
| AWS Lake Formation  |  | 
| Amazon Managed Streaming for Apache Kafka (Amazon MSK)  |  | 
| Amazon OpenSearch Service  |  | 
| Amazon QuickSight  |  | 


## アプリケーション統合: 
| サービス名 | 概要 | 
| --- | --- | 
| Amazon MQ   |  | 
| Amazon Simple Notification Service (Amazon SNS)   |  | 
| Amazon Simple Queue Service (Amazon SQS)   |  | 
| AWS Step Functions   |  | 


## コンピューティング: 
| サービス名 | 概要 | 
| --- | --- | 
| AWS Auto Scaling   |  | 
| Amazon EC2    |  | 
| AWS Lambda  |  | 


## データベース:
| サービス名 | 概要 | 
| --- | --- | 
| Amazon DocumentDB (MongoDB 互換)  |  | 
| Amazon DynamoDB  |  | 
| Amazon ElastiCache  |  | 
| Amazon Neptune  |  | 
| Amazon RDS  |  | 
| Amazon Redshift  |  | 
| Amazon Timestream  |  | 

## フロントエンドのウェブとモバイル:
| サービス名 | 概要 | 
| --- | --- | 
| Amazon API Gateway  |  | 
| AWS AppSync  |  | 
| Amazon Simple Email Service (Amazon SES)  |  | 

## マネジメントとガバナンス:
| サービス名 | 概要 | 
| --- | --- | 
| AWS CloudFormation  |  | 
| AWS CloudTrail  |  | 
| Amazon CloudWatch  |  | 
| AWS Trusted Advisor  |  | 


## 機械学習:
| サービス名 | 概要 | 
| --- | --- | 
| Amazon SageMaker  |  | 


## 移行と転送:
| サービス名 | 概要 | 
| --- | --- | 
| AWS Database Migration Service (AWS DMS)  |  | 
|AWS DataSync  |  | 
| AWS Snowball  |  | 
| AWS Transfer Family  |  | 


## ネットワークとコンテンツ配信:
| サービス名 | 概要 | 
| --- | --- | 
| AWS Direct Connect  |  | 
| Elastic Load Balancing (ELB)  |  | 
| Amazon VPC  |  | 


## セキュリティ、アイデンティティ、コンプライアンス:
| サービス名 | 概要 | 
| --- | --- | 
| AWS Artifact  |  | 
| AWS Certificate Manager (ACM)  |  | 
| AWS CloudHSM  |  | 
| Amazon Cognito  |  | 
| AWS IAM Identity Center (AWS Single Sign-On の後継)  |  | 
| AWS Identity and Access Management (IAM)  |  | 
| AWS Key Management Service (AWS KMS)  |  | 
| Amazon Macie  |  | 
| AWS Secrets Manager  |  | 


## ストレージ:
| サービス名 | 概要 | 
| --- | --- | 
| Amazon Elastic Block Store (Amazon EBS)  |  | 
| Amazon S3  |  | 
| Amazon S3 Glacier   |  | 

# 各機能の特徴

## 分析:
### Amazon Athena	
>Amazon Athena は、オープンソースフレームワーク上に構築されたサーバーレスのインタラクティブな分析サービスで、オープンテーブルとファイル形式をサポートしています。Athena は、ペタバイト規模のデータが存在する場所で分析するための簡素化された柔軟な方法を提供します。

> Amazon Simple Storage Service (S3) データレイクと 25 以上のデータソース (オンプレミスデータソースや SQL または Python を使用した他のクラウドシステムを含む) からデータを分析したり、アプリケーションを構築したりできます。

>Athena は、オープンソースの Trino および 
Presto エンジンと Apache Spark フレームワーク上に構築されており、プロビジョニングや設定は不要です。

- Amazon Athena は、Amazon Web Services（AWS）が提供するデータ分析サービスです。Amazon S3 に保存されたデータを、標準的な SQL クエリを使用して分析することができます。
- **Athena の特徴は次のとおりです。**
  - サーバレス型で、インフラの設定や管理が不要
  - 大規模なデータ分析や複雑なクエリに適している
  - 実行されたクエリに対してのみ料金がかかり、1TB 毎に 5USD となっている
  - 暗号化されたデータに対してもクエリを実行できる
  - AWS Key Management Service（KMS）を併用することで、クエリの実行結果を暗号化できる
- **Athena は、次の場合に適しています:**
  - 大規模なデータ分析が必要な場合
  - 複雑なクエリが必要な場合
  - ペタバイト規模のデータが存在する場所で分析する場合
- **Athena は、次の手順で使用できます:**
  - Amazon S3 に保存されたデータを指定する
  - フィールドを定義する
  - クエリを投げる
- 結果は数秒で得られます。
### Amazon CloudSearch	
> Amazon CloudSearch は AWS クラウドにおけるマネージド型サービスであり、ウェブサイトまたはアプリケーション向けの検索ソリューションを容易かつコスト効率良く設定、管理、スケールできます。
### Amazon EMR	
> Amazon EMR とは、Apache Spark、Apache Hive、Presto などのオープンソースフレームワークを使用して、ペタバイトスケールのデータ処理、相互分析、機械学習を行なう業界をリードするクラウドビッグデータソリューションです。

### AWS Glue	
> AWS Glue は、サーバーレスなデータ統合サービスで、分析、機械学習 (ML)、アプリケーション開発用に、複数のソースからデータを検出、準備、移動、統合することをより容易にします。

- AWS Glue（読み方：グルー）は、Amazonが提供するサーバーレスのデータ統合サービスです。データ分析、機械学習、アプリケーション開発のために、70 を超えるデータソースからデータ検出、抽出、結合などを簡単に行うことができます。
- **AWS Glue の機能には、次のようなものがあります:**
  - 70 を超えるデータソースを検出して接続する
  - 一元化されたデータカタログでデータを管理する
  - ETL パイプラインを視覚的に作成、実行、モニタリングする
  - データレイクにデータをロードする
  - さまざまなデータソースのメタデータを管理する
  - AWS Glue Data Catalog で、データ形式、スキーマ、ソースに関する情報を保存およびクエリする
  - AWS Glue DataBrew で、データをクリーンアップおよび正規化する

> AWS Glue は、完全マネージド型のサービスで、導入にあたってインストールするサーバーなどを用意する必要はありません。また、オンプレミス型ETLツールに比べてコストを抑えて利用できます。


### Amazon Kinesis	
>Amazon Kinesis でストリーミングデータをリアルタイムで収集、処理、分析することが簡単になるため、インサイトを適時に取得して新しい情報に迅速に対応できます。Amazon Kinesis は、アプリケーションの要件に最適なツールを柔軟に選択できるだけでなく、あらゆる規模のストリーミングデータをコスト効率良く処理するための主要機能を提供します。

- Amazon Kinesis は、動画や音声、IoT機器などのストリーミングデータをリアルタイムで収集して処理するフルマネージド型分析サービスです。

- **Amazon Kinesis の機能には、次のようなものがあります:**
  - 全データの収集が終わるのを待たずに処理を行う
  - 直ちに応答を開始する
  - インサイトをすぐに取得して迅速に対応する
  - 動画を簡単かつ安全にストリーミングできる
  - 入力ストリームとアプリケーション内ストリームの２つを指定する
  - SQLクエリ文を記載してデータを集計する
  - リアルタイム分析をダッシュボード上で管理する
  - 異常検知を行う
  - 登録されたデータを複数のアプリケーションから参照する
  - ストリーミングデータを確実にキャプチャおよび変換する
  - データレイク、データストア、および分析サービスに配信する

- **Amazon Kinesis には、次の機能があります:**
  - Amazon Kinesis Video Streams
  - Amazon Kinesis Data Streams
  - Kinesis Data Analytics
  - Amazon Kinesis Data Firehose
### AWS Lake Formation	
> 分析や機械学習のためのデータを一元管理、保護、およびグローバルに共有することが容易になります。

- AWS Lake Formation は、データレイクの構築、セキュア化、管理を簡単に実行できるフルマネージドサービスです。データレイクは、さまざまなデータを安全で一元的に収納するものです。
- AWS Lake Formation は、データレイクの作成に通常必要となる手動での複雑な手順の多くを簡素化し、自動化します。数日で安全なデータレイクをセットアップできます。
- AWS Lake Formation を使用すると、分析や機械学習のためのデータを一元管理、保護、およびグローバルに共有することが容易になります。
- AWS Lake Formation は、ほぼAWSの各種サービスをラップしたもので、Glue、IAM、S3 などがあります。
- データレイクを作るには、収集、保存、変換、活用の4つのステップが必要です。
### Amazon Managed Streaming for Apache Kafka (Amazon MSK)	
> Amazon MSK では、フルマネージド Apache Kafka により、ストリーミングデータの取り込みと処理をリアルタイムで簡単に行うことができます。


### Amazon OpenSearch Service	
>Amazon OpenSearch Service は、AWS で OpenSearch (現在 Apache Lucene 9 をサポート) クラスターを安全かつ費用対効果の高い方法でより簡単にデプロイ、運用、スケールすることを可能にするフルマネージドサービスです。

- Amazon OpenSearch Service は、AWS クラウドで OpenSearch クラスターをデプロイ、オペレーション、スケーリングを容易にするマネージドサービスです。﻿
- Amazon OpenSearch Service は、ドキュメント、メッセージ、ログなどのさまざまなデータソースに対して、Dashboards Query Language（DQL）を使用することでデータの分析や可視化ができるサービスです。﻿
- **Amazon OpenSearch Service は、次の特徴があります:**
  - ペタバイト規模の大量テキストを扱える検索エンジン 
  - 検索速度や分析柔軟性に優れている
  - データ蓄積や分析環境を簡単に構築できる
  - 安全かつ費用対効果の高い方法で OpenSearch クラスターをデプロイ、運用できる
> Amazon OpenSearch Service は、Elasticsearchとは異なるサービスです。Elasticsearchは、Amazon OpenSearch Serviceの開発元であるElasticが開発した全文検索エンジンです。
### Amazon QuickSight	
- Amazon QuickSight は、AWS が提供するビジネスインテリジェンス (BI) サービスです。このサービスでは、高速かつ簡単に情報を可視化することができます。
- **Amazon QuickSight の特徴は次のとおりです:**
  - S3 や RDS などの AWS サービス上にあるデータや、ローカルの CSV ファイルなどを使用して分析を行うことができる
  - ダッシュボードおよびレポートを簡単かつ迅速に作成し、アクセスすることができる
  - 少ないコストから始められる
  - 将来予測や異常検出の仕組みを実現できる
  - ユーザーの管理がしやすい
  - AWS 内のデータ統合が簡単
  - アップデート・メンテナンスが不要
  - 使用料金が従量課金制になっている
  - 数万人のユーザー利用にも対応できる
  - グローバル展開にも幅広く対応
- **Amazon QuickSight の料金は、1 セッションあたり 0.30 USD です。ただし、閲覧者 1 人あたり 5 USD/月の上限が設定されています。**



## アプリケーション統合:
### Amazon MQ	
### Amazon Simple Notification Service (Amazon SNS)	
### Amazon Simple Queue Service (Amazon SQS)	
### AWS Step Functions	


## コンピューティング:
### AWS Auto Scaling	
### Amazon EC2	
### AWS Lambda	
## データベース:
### Amazon DocumentDB (MongoDB 互換)	
- MongoDB と互換性のある非リレーショナルデータベースサービスです。MongoDB のワークロードを大規模に運用するために必要なパフォーマンス、スケーラビリティ、可用性を提供するために設計されています。
- **Amazon DocumentDB の特徴は次のとおりです。**
  - 高速で信頼性が高く、完全マネージド型
  - MongoDB と互換性のあるデータベースを簡単にセットアップ、運用、スケールできる
  - JSON データの保存、クエリ、インデックス作成を容易にする
  - 構築の簡素化、自動スケーリングや自動パッチ適用など運用の簡素化を図れる
  - クラスターストレージを容量が増えくると自動的にストレージボリュームを拡張する
- **Amazon DocumentDB は、次の特徴があります。**
  - NoSQL
  - ドキュメント指向
  - スキーマレス
  - シャーディング, レプリケーション
  
> Amazon DocumentDB は、2022年10月現在、MongoDB 3.6および4.0のドライバーおよびツールと互換性があります。

### Amazon DynamoDB	
### Amazon ElastiCache	
### Amazon Neptune	
### Amazon RDS	
### Amazon Redshift	
### Amazon Timestream	
- Amazon Timestream は、高速かつスケーラブルなサーバーレス時系列データベースサービスです。2022年7月より東京リージョンで利用可能になりました。
- **Amazon Timestream は、次の特徴があります:**
  - 低コストかつ高パフォーマンス
  - キャパシティの管理は不要
  - コンピューティングリソースとストレージを自動で拡張
-**Amazon Timestream は、次の用途に使用できます:**
  - IoT アプリケーションのセンサーデータ
  - DevOps ユースケースのメトリクス
  - クリックストリームデータ分析

## フロントエンドのウェブとモバイル:
### Amazon API Gateway	
### AWS AppSync	
- AWS AppSync は、Amazon Web Services（AWS）が提供する、サーバーレスの GraphQL および Pub/Sub API を作成できるサービスです。このサービスは、アプリケーションの開発を簡素化するために、単一のエンドポイントを通じて安全にデータの照会、更新、公開を行うことができます。
- **AWS AppSync は、次のことができます:**
  - 1つ以上のデータソースからデータにアクセスする
  - 操作統合のためのAPIを作成できる
  - DynamoDBテーブルやLambda関数などをデータソースとしたAPIを作成できる
  - 複数のデータベースからデータをまとめて取得できる
  - モバイルのアプリケーションのために、オフライン時のアクセスと、オンラインに復帰した際に競合を解決するための機能を備えた、データ同期機能を提供できる
> AWS AppSync は、完全マネージド型サービスなので、セットアップ、管理、保守は必要ありません。

### Amazon Simple Email Service (Amazon SES)	


## マネジメントとガバナンス:
### AWS CloudFormation	
### AWS CloudTrail	
### Amazon CloudWatch	
### AWS Trusted Advisor	


## 機械学習:
### Amazon SageMaker	
- Amazon SageMaker（アマゾン セージメイカー）は、AWSが提供するフルマネージド型の機械学習サービスです。このサービスでは、トレーニングデータの前処理、教師データの作成、機械学習モデルの構築・学習、学習済みモデルのデプロイなど、一連のプロセスを行うことができます。
- SageMakerを使用すると、機械学習モデルをすばやく簡単に構築してトレーニングし、本番環境でホストされている環境に直接デプロイできます。また、アルゴリズムなどをある程度ユーザー側で制御できるようなサービスです。
- **SageMakerには、次のような機能があります:**
  - Amazon SageMaker Studio：データの準備から構築、トレーニング、デプロイまで、すべての機械学習開発ステップを実行するための専用ツールにアクセスできる単一のウェブベースの視覚的インターフェイスを提供する統合開発環境 (IDE)
  - SageMaker Data Wrangler：データ品質 (欠損値、重複行、データ型など) を自動的に検証し、データの異常 (外れ値、クラスの不均衡、データ漏洩など) を検出するのに役立つデータ品質とインサイトレポートを提供
  - Amazon SageMaker Neo：TensorFlowやPytorchといった各種AIフレームワークモデルを、精度を損なうことなく変換し、ターゲットハードウェア用にモデルを最適化できるサービス

## 移行と転送:
### AWS Database Migration Service (AWS DMS)	
### AWS DataSync	
- AWS DataSync は、AWS へのデータ移行を簡素化および高速化するオンラインデータ移行および検出サービスです。オンプレミスのストレージ、エッジロケーション、他のクラウド、および AWS ストレージ間でデータを迅速かつ安全に移行するのをサポートします。
- **AWS DataSync のメリットは次のとおりです:**
  - 転送の簡素化と自動化ができる
  - 安全にデータを転送できる
  - より速くデータを移動できる
  - 運用費用の削減ができる
- **AWS DataSync は、次のストレージサービスとのデータ転送をサポートしています:**
  - Amazon S3
  - Amazon Elastic File System (Amazon EFS)
  - Amazon FSx for Windows ファイルサーバー
- AWS DataSync の料金は、移行するデータ量のみを支払う、シンプルで予測可能な料金体系です。お客様の AWS リージョンに応じたギガバイト単位の定額制に基づいています。
- AWS DataSync は、データを自動的に移動・移行する必要があるワークロードに適しています。

### AWS Snowball	
### AWS Transfer Family	


## ネットワークとコンテンツ配信:
### AWS Direct Connect	
- AWS Direct Connect は、AWS と自社の拠点やデータセンターをプライベート接続するクラウドサービスです。このサービスは、標準のイーサネット光ファイバケーブルを介して、お客様の内部ネットワークを AWS Direct Connect ロケーションに接続します。
- AWS Direct Connect のメリットには、次のようなものがあります。
  - 通信速度が安定する
  - 大容量のデータ通信が可能になる
  - 初期費用がかからない
  - 基本料金がない
  - データ転送量が割り引かれる
  - 安全性が高まる
  - VPN を併用できる
- AWS Direct Connect は、インターネット回線とは分離されており、外部からの盗聴や改ざん、なりすましなどの危険性が少ないと言われています。
- AWS Direct Connect のデメリットには、次のようなものがあります。
  - 費用が高い
  - 接続が遅い
  - セキュリティが不安
  - 従量課金のため利用者が増えると費用が上がる
### Elastic Load Balancing (ELB)	
### Amazon VPC	


## セキュリティ、アイデンティティ、コンプライアンス:
### AWS Artifact	
### AWS Certificate Manager (ACM)	
### AWS CloudHSM	
### Amazon Cognito	
### AWS IAM Identity Center (AWS Single Sign-On の後継)	
### AWS Identity and Access Management (IAM)	
### AWS Key Management Service (AWS KMS)	
### Amazon Macie	
-Amazon Macie は、機械学習とパターンマッチングを利用して、機密データを検出して保護するデータセキュリティサービスです。S3バケットから機密データを検出できます。
- **Amazon Macie の特徴は次のとおりです。**
  - 機械学習とパターンマッチングを使用
  - S3環境で継続的にチェックを行い、アラート検出、自動対応ができる
  - データのセキュリティリスクを可視化する
  - データ分類のベストプラクティスとして活用を推奨されている
- Amazon Macie を有効にするには、次の手順を実行します。
  1. Amazon Macie コンソール（https://console.aws.amazon.com/macie/ ）を開く。
  1. AWS リージョンページの右上隅にあるセレクターを使用して、有効にするリージョンを選択する。

### AWS Secrets Manager	


## ストレージ:
### Amazon Elastic Block Store (Amazon EBS)	
### Amazon S3	
### Amazon S3 Glacier



