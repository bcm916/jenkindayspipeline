pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
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
            sh 'go version'
          }
        }
      }
    }
  }
}