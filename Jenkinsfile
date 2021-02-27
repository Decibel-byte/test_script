pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      agent any
      environment {
        key = 'cje'
      }
      steps {
        echo 'echo edited placehoder'
      }
    }

    stage('archiving') {
      steps {
        archiveArtifacts(artifacts: 'pipeline.log', fingerprint: true)
      }
    }

  }
  environment {
    key = 'cje'
  }
}