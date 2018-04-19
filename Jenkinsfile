pipeline {
  agent {
    node {
      label 'jdk9'
    }
    
  }
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
}