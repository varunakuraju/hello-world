pipeline {
  agent any
  stages {
    stage('anyname1') {
      parallel {
        stage('anyname1') {
          steps {
            sh 'ls -al'
            sh 'ps -ef'
          }
        }

        stage('parallel stage') {
          steps {
            echo 'some message printed'
          }
        }

      }
    }

  }
}