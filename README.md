# cloud-serverless-app
A cloud-native, serverless web application demonstrating modern cloud engineering best practices.

## Architecture & Design

- **Services Used**:
  - **AWS Lambda / GCP Cloud Functions**: Event-driven compute
  - **API Gateway / Cloud RUN**: HTTP Endpoints
  - **S3 / GCS**: Static content hosting
  - **DynamoDB / Firestore**: Serverless databse
  - **IAM Roles / Service Accounts**: Security and access management

- **Diagram**: *(API Gataway → Lambda → Database → Response)*
