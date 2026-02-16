# Serverless muti-tier task management architecture
Scalable serverless multi-tier architecture with IaC, enterprise security, and cost-optimized event-driven design

## App Capabilities
- Create / read / update / delete tasks
- Generate pre-signed S3 upload URL for images
- Publish task event notifications via SNS

## AWS Services Used
- Frontend: `S3 + CloudFront`
- Backend: `API Gateway + Lambda (Python 3.12)`
- Database: `DynamoDB`
- Notifications: `SNS (email subscription optional)`
- Monitoring: `CloudWatch alarms`
- Security: `IAM least privilege`, `WAF (optional)`
