Existing resources to save time when demoing:
Region us-west-1 (cbqa-talks-demo)
-IAM Role for EC2
-EC2 with security group and IAM Role
-CodeCommit

Resources to create manually:
-CodeBuild Project
-CodeDeploy Project
-CodePipeline

1. Create pipeline with source and build stage
2. Add Deploy stage
2. Add manual step
3. Add version change in code
4. Make test to fail
5. Show CloudFormation EC2 script