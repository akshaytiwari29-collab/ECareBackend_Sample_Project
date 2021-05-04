pipeline {
  agent any
  stages {
    stage('') {
      steps {
        ecrListImages()
      }
    }

  }
  environment {
    AWS_ECS_CLUSTER = 'ch-dev'
  }
}