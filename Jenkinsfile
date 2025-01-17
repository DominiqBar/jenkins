pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            sh 'date'
          }
        }

        stage('Stage 2') {
          steps {
            sh 'dpkg -l  > /tmp/paquets'
          }
        }

      }
    }

    stage('Stage 3') {
      steps {
        sh 'echo "Stage 3"'
      }
    }

  }
}