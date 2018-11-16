pipeline {
  agent any
  stages {
    stage('step-1') {
      steps {
        sh 'echo "hello world i try to build a project "'
      }
    }
    stage('build') {
      steps {
        sh 'file 45'
        sh 'echo "testing"'
      }
    }
    stage('dep') {
      steps {
        sh 'echo "finis your Project and clear no error"'
      }
    }
  }
}
