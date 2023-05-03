pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name alb --template-body file://alb-asg.yaml --region 'ap-northeast-1'"
              }
             }
            }
            }
