pipeline {
  agent any
  stages {
    stage('stage') {
      agent any
      environment {
        key = 'cje'
      }
      steps {
        sh 'date'
      }
    }

  }
  environment {
    key = 'cje'
  }
}