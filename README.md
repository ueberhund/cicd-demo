# cicd-demo

This solution demonstrates how to use a CI/CD that deploys CloudFormation templates via AWS CodePipeline. 

- [demo-stack.yml](demo-stack.yml) - this file is the demo template that gets deployed as part of the CI/CD stack. This stack assumes you have a SSM Parameter Store value already created and called `/notificationEmailAddress`. 
- [basic-pipeline.yml](basic-pipeline.yml) - this file sets up a basic CI/CD pipeline within AWS CodePipeline. Use the CloudFormation console to deploy this basic pipeline. This template assumes you already have a connection set up to your GitHub repo. You can view/edit your existing connections under CodePipeline -> Settings.
