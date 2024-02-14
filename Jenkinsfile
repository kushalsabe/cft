pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name my-stack1 --template-body file://cft.yaml --capabilities CAPABILITY_NAMED_IAM --region 'ap-northeast-2'"
              }
             }
            }
            }
