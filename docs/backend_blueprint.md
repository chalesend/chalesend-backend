# High Level System Architecture
<img width="671" height="443" alt="image" src="https://github.com/user-attachments/assets/df136dee-695b-494e-a3e7-9a9816e07b35" />
<img width="2006" height="1034" alt="image" src="https://github.com/user-attachments/assets/d7f5845f-255f-4e9b-b592-a6605bc6119f" />
✔ Client: Flutter (iOS/Android)
✔ API Layer: AWS API Gateway
✔ Compute: AWS Lambda (Python → FastAPI using Mangum adapter)
✔ Database: Aurora PostgreSQL Serverless v2
✔ Storage: S3 (documents, logs, webhook archives)
✔ Auth: AWS Cognito (JWT tokens)
✔ Messaging: SNS + SQS (webhooks, retry queues, notifications)
✔ Monitoring: CloudWatch + X-Ray
✔ Integrations:
              SendSprint (RaaS provider / MTL Holder)
              Flutterwave (Sender-side payment initiation)
              Nium (future multi-region payouts)

