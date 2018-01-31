pipeline {
  agent any
  stages {
    stage('F5 Active Stage') {
      parallel {
        stage('F5 Active Stage') {
          steps {
            mail(subject: 'F5 is active', body: 'F5', from: 'jenkinsranveer', replyTo: 'pranveer@zeomega.com', to: 'pranveer@zeomega.com')
          }
        }
        stage('F5 active') {
          steps {
            echo 'No Mail'
          }
        }
      }
    }
    stage('F5 Stage') {
      parallel {
        stage('F5 Stage') {
          steps {
            echo 'F5 Active'
          }
        }
        stage('F5 stage') {
          steps {
            echo 'No F5'
          }
        }
      }
    }
    stage('F5') {
      steps {
        sh './shell.sh'
        sh 'echo "Test" >12.txt'
      }
    }
  }
}