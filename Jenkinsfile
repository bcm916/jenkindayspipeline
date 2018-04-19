pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'Hello'
          }
        }
        stage('') {
          steps {
            echo 'I want pecan pie!!!'
          }
        }
      }
    }
  }
}