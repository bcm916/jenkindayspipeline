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
            sh 'java -version'
          }
        }
      }
    }
  }
  environment {
    label = 'jdk9'
  }
}