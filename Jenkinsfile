pipeline {
  agent none
  stages {
    stage('step-1') {
      parallel {
        stage('step-1') {
          steps {
            sh 'echo "hello world"'
          }
        }
        stage('step-2') {
          steps {
            sh 'echo "hello dunia"'
          }
        }
      }
    }
  }
}