pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        ecrListImages()
      }
    }

  }
  environment {
    AWS_ACCESS_KEY_ID = credentials('aws-key-id')
    AWS_SECRET_ACCESS_KEY = credentials('aws-secret-key')
    AWS_ECS_CLUSTER = 'ch-dev'
  }
}