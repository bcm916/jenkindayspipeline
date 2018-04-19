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
        stage('world') {
          steps {
            echo 'I want pecan pie!!!'
          }
        }
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}