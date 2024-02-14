pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name YourStackName --template-body file://your-template.yaml --capabilities CAPABILITY_NAMED_IAM --region 'ap-northeast-2'"
              }
             }
            }
            }
