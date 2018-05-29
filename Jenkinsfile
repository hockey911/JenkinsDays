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
        stage('error') {
          steps {
            echo 'Hal knows all'
          }
        }
      }
    }
    stage('asdf') {
      steps {
        sleep 9
      }
    }
    stage('jkl;') {
      parallel {
        stage('jkl;') {
          steps {
            dir(path: 'fart') {
              echo 'asdf'
            }
            
            dir(path: 'fartb') {
              echo 'lol'
            }
            
          }
        }
        stage('fart1') {
          steps {
            echo 'fart'
          }
        }
      }
    }
  }
}