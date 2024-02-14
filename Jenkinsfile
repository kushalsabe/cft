pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name kushal --template-body file://cft.yaml --region 'ap-northeast-2'"
              }
             }
            }
            }
