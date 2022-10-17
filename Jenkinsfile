pipeline {
  agent any
  options {
    ansiColor('xterm')
  }
  stages {
    stage('Download dependencies') {
      steps {
        sh '''go mod init dispatch
        go get
        go build'''
      }
    }
  }
}