pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name alb --template-body file://alb-asg --region 'ap-south-1'"
              }
             }
            }
            }
