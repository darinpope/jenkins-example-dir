pipeline {
  agent any
  stages {
    stage('full path') {
      steps {
        sh 'cat my-project/file.txt'
      }
    }
    stage('use dir') {
      steps {
        dir('my-project') {
          sh 'cat file.txt'
        }
      }
    }
  }
}