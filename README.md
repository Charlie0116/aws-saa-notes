# AWS SAA 学習ログ

## 概要
このリポジトリは、AWS Certified Solutions Architect – Associate (SAA) 試験の学習ログです。

## 目的：
- AWS SAA の勉強内容を自分用に整理する
- 後から見返せるように分野ごとにメモを残す
- 学習の継続を GitHub で見える化する

## ファイル構成

SAAで頻出の分野ごとに Markdown ファイルを分けています。

- `vpc-network.md`  
  - VPC / Subnet / Route Table / NAT Gateway / Internet Gateway  
  - Security Group / NACL / VPC Endpoint / Flow Logs などネットワーク周り全般

- `ec2-elb-asg.md`  
  - EC2 / AMI / EBS / Auto Scaling Group  
  - ALB / NLB / ターゲットグループ / ヘルスチェック など

- `s3-ebs.md`  
  - S3（ストレージクラス、ライフサイクル、バケットポリシー など）  
  - EBS（ボリュームタイプ、スナップショット など）

- `database-rds-dynamo.md`  
  - RDS / Aurora（マルチAZ、リードレプリカ、バックアップ）  
  - DynamoDB（パーティションキー、RCU/WCU、GSI/LSI など）

- `iam-security.md`  
  - IAMユーザー / ロール / ポリシー / MFA  
  - KMS / Secrets Manager / SSM Parameter Store などセキュリティ周り

- `serverless-messaging.md`  
  - Lambda / API Gateway  
  - SQS / SNS / EventBridge など

必要に応じて今後ファイルを追加・分割します。

---

## 記録スタイル

各ファイルは「サービスごとの参考書」ではなく、**日々の学習ログ**として運用しています。

- 模擬試験で間違えた点、あいまいだった点を優先してメモ
- 自分なりの例え・図・気付きもそのまま残す

完璧にきれいなノートではなく、「実際に悩んだ点・間違えた点」に重きを置いています。