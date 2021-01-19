pipeline {
  agent any
  stages {
    stage('anyname1') {
      parallel {
        stage('anyname1') {
          steps {
            sh 'ls -al'
            sh 'ps -ef'
            sh 'ls -a'
          }
        }

        stage('parallel stage') {
          steps {
            echo 'some message printed'
          }
        }

        stage('normal stage') {
          steps {
            sh 'man top'
          }
        }

      }
    }

  }
}
