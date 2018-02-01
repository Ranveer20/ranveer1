pipeline {
  agent none
  stages {
    stage('text1') {
      parallel {
        stage('text1') {
          steps {
            echo 'Hello '
          }
        }
        stage('text2') {
          steps {
            sh 'echo "Hello Script"'
          }
        }
      }
    }
    stage('finish') {
      steps {
        echo 'bye!!!'
      }
    }
  }
}