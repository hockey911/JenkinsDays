pipeline {
  agent any
  stages {
    stage('Open the pod bay doors hal') {
      steps {
        echo 'Im sorry Dave. Im afraid i cant do that. '
      }
    }
    stage('SH') {
      parallel {
        stage('SH') {
          steps {
            sh 'java -version'
          }
        }
        stage('') {
          steps {
            echo 'Hal knows all'
          }
        }
      }
    }
  }
}