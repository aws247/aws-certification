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
### Amazon CloudSearch	
### Amazon EMR	
### AWS Glue	
- AWS Glue（読み方：グルー）は、Amazonが提供するサーバーレスのデータ統合サービスです。データ分析、機械学習、アプリケーション開発のために、70 を超えるデータソースからデータ検出、抽出、結合などを簡単に行うことができます。﻿
- **AWS Glue の機能には、次のようなものがあります:﻿**
  - 70 を超えるデータソースを検出して接続する
  - 一元化されたデータカタログでデータを管理する
  - ETL パイプラインを視覚的に作成、実行、モニタリングする
  - データレイクにデータをロードする
  - さまざまなデータソースのメタデータを管理する
  - AWS Glue Data Catalog で、データ形式、スキーマ、ソースに関する情報を保存およびクエリする
  - AWS Glue DataBrew で、データをクリーンアップおよび正規化する
> AWS Glue は、完全マネージド型のサービスで、導入にあたってインストールするサーバーなどを用意する必要はありません。また、オンプレミス型ETLツールに比べてコストを抑えて利用できます。﻿


### Amazon Kinesis	
### AWS Lake Formation	
### Amazon Managed Streaming for Apache Kafka (Amazon MSK)	
### Amazon OpenSearch Service	
### Amazon QuickSight	


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
- MongoDB と互換性のある非リレーショナルデータベースサービスです。MongoDB のワークロードを大規模に運用するために必要なパフォーマンス、スケーラビリティ、可用性を提供するために設計されています。﻿
- **Amazon DocumentDB の特徴は次のとおりです。﻿**
  - 高速で信頼性が高く、完全マネージド型
  - MongoDB と互換性のあるデータベースを簡単にセットアップ、運用、スケールできる
  - JSON データの保存、クエリ、インデックス作成を容易にする
  - 構築の簡素化、自動スケーリングや自動パッチ適用など運用の簡素化を図れる
  - クラスターストレージを容量が増えくると自動的にストレージボリュームを拡張する
- **Amazon DocumentDB は、次の特徴があります。﻿**
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


## フロントエンドのウェブとモバイル:
### Amazon API Gateway	
### AWS AppSync	
- AWS AppSync は、Amazon Web Services（AWS）が提供する、サーバーレスの GraphQL および Pub/Sub API を作成できるサービスです。このサービスは、アプリケーションの開発を簡素化するために、単一のエンドポイントを通じて安全にデータの照会、更新、公開を行うことができます。﻿
- **AWS AppSync は、次のことができます:﻿**
  - 1つ以上のデータソースからデータにアクセスする
  - 操作統合のためのAPIを作成できる
  - DynamoDBテーブルやLambda関数などをデータソースとしたAPIを作成できる
  - 複数のデータベースからデータをまとめて取得できる
  - モバイルのアプリケーションのために、オフライン時のアクセスと、オンラインに復帰した際に競合を解決するための機能を備えた、データ同期機能を提供できる
> AWS AppSync は、完全マネージド型サービスなので、セットアップ、管理、保守は必要ありません。﻿

### Amazon Simple Email Service (Amazon SES)	


## マネジメントとガバナンス:
### AWS CloudFormation	
### AWS CloudTrail	
### Amazon CloudWatch	
### AWS Trusted Advisor	


## 機械学習:
### Amazon SageMaker	
- Amazon SageMaker（アマゾン セージメイカー）は、AWSが提供するフルマネージド型の機械学習サービスです。このサービスでは、トレーニングデータの前処理、教師データの作成、機械学習モデルの構築・学習、学習済みモデルのデプロイなど、一連のプロセスを行うことができます。﻿
- SageMakerを使用すると、機械学習モデルをすばやく簡単に構築してトレーニングし、本番環境でホストされている環境に直接デプロイできます。また、アルゴリズムなどをある程度ユーザー側で制御できるようなサービスです。﻿
- **SageMakerには、次のような機能があります:﻿**
  - Amazon SageMaker Studio：データの準備から構築、トレーニング、デプロイまで、すべての機械学習開発ステップを実行するための専用ツールにアクセスできる単一のウェブベースの視覚的インターフェイスを提供する統合開発環境 (IDE)
  - SageMaker Data Wrangler：データ品質 (欠損値、重複行、データ型など) を自動的に検証し、データの異常 (外れ値、クラスの不均衡、データ漏洩など) を検出するのに役立つデータ品質とインサイトレポートを提供
  - Amazon SageMaker Neo：TensorFlowやPytorchといった各種AIフレームワークモデルを、精度を損なうことなく変換し、ターゲットハードウェア用にモデルを最適化できるサービス

## 移行と転送:
### AWS Database Migration Service (AWS DMS)	
### AWS DataSync	
- AWS DataSync は、AWS へのデータ移行を簡素化および高速化するオンラインデータ移行および検出サービスです。オンプレミスのストレージ、エッジロケーション、他のクラウド、および AWS ストレージ間でデータを迅速かつ安全に移行するのをサポートします。﻿
- **AWS DataSync のメリットは次のとおりです:﻿**
  - 転送の簡素化と自動化ができる
  - 安全にデータを転送できる
  - より速くデータを移動できる
  - 運用費用の削減ができる
- **AWS DataSync は、次のストレージサービスとのデータ転送をサポートしています:﻿**
  - Amazon S3
  - Amazon Elastic File System (Amazon EFS)
  - Amazon FSx for Windows ファイルサーバー
- AWS DataSync の料金は、移行するデータ量のみを支払う、シンプルで予測可能な料金体系です。お客様の AWS リージョンに応じたギガバイト単位の定額制に基づいています。﻿
- AWS DataSync は、データを自動的に移動・移行する必要があるワークロードに適しています。﻿

### AWS Snowball	
### AWS Transfer Family	


## ネットワークとコンテンツ配信:
### AWS Direct Connect	
- AWS Direct Connect は、AWS と自社の拠点やデータセンターをプライベート接続するクラウドサービスです。このサービスは、標準のイーサネット光ファイバケーブルを介して、お客様の内部ネットワークを AWS Direct Connect ロケーションに接続します。﻿
- AWS Direct Connect のメリットには、次のようなものがあります。﻿
  - 通信速度が安定する
  - 大容量のデータ通信が可能になる
  - 初期費用がかからない
  - 基本料金がない
  - データ転送量が割り引かれる
  - 安全性が高まる
  - VPN を併用できる
- AWS Direct Connect は、インターネット回線とは分離されており、外部からの盗聴や改ざん、なりすましなどの危険性が少ないと言われています。﻿
- AWS Direct Connect のデメリットには、次のようなものがあります。﻿
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
-Amazon Macie は、機械学習とパターンマッチングを利用して、機密データを検出して保護するデータセキュリティサービスです。S3バケットから機密データを検出できます。﻿
- **Amazon Macie の特徴は次のとおりです。﻿**
  - 機械学習とパターンマッチングを使用
  - S3環境で継続的にチェックを行い、アラート検出、自動対応ができる
  - データのセキュリティリスクを可視化する
  - データ分類のベストプラクティスとして活用を推奨されている
- Amazon Macie を有効にするには、次の手順を実行します。﻿
  1. Amazon Macie コンソール（https://console.aws.amazon.com/macie/ ）を開く。
  1. AWS リージョンページの右上隅にあるセレクターを使用して、有効にするリージョンを選択する。

### AWS Secrets Manager	


## ストレージ:
### Amazon Elastic Block Store (Amazon EBS)	
### Amazon S3	
### Amazon S3 Glacier



