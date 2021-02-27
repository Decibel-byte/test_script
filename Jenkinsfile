pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      parallel {
        stage('Fluffy Build') {
          agent any
          environment {
            key = 'cje'
          }
          steps {
            echo 'echo edited placehoder'
          }
        }

        stage('Fluffy test') {
          steps {
            sh 'sleep 5'
            sh 'echo "Success"'
          }
        }

        stage('Fluffy Deploy') {
          steps {
            sh 'echo "Placeholder"'
          }
        }

      }
    }

  }
  environment {
    key = 'cje'
  }
}