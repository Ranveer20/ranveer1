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
            echo 'My Message'
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