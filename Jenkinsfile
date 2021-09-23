pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name emrcluster --template-body file://cftemplate1.yml --region 'us-east-2'"
              }
            }
        }
    }
