pipeline {
  agent none
  stages {
    stage('step-1') {
      steps {
        sh '''def branch = readFile(\'branch\').trim()
if (branch == master)
{echo "hello world"}'''
      }
    }
  }
}