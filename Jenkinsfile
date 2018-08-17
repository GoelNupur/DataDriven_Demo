pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'test 1'
          }
        }
        stage('build2') {
          steps {
            echo 'test 2'
          }
        }
      }
    }
  }
  environment {
    stage = 'build'
  }
}