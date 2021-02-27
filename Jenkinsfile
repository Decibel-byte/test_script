pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('stage') {
      agent any
      environment {
        key = 'cje'
      }
      steps {
        sh 'date'
        sh 'echo "Hi Aziz!"'
      }
    }

  }
  environment {
    key = 'cje'
  }
}