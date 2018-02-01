pipeline {
  agent none
  stages {
    stage('text1') {
      parallel {
        stage('text1') {
          steps {
            sh 'echo "Hello Script"'
          }
        }
        stage('text2') {
          steps {
            echo 'hi ranveer'
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