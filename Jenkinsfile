pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        echo 'Hello I am learning!!'
      }
    }

    stage('seondstage') {
      steps {
        pwd(tmp: true)
      }
    }

    stage('third stage') {
      steps {
        sleep 10
      }
    }

      stage('forth stage') {
      steps {
        sleep 10
      }
    }

    stage('script stage') {
      steps {
        sh '''!#/bin/bash
pwd
date
echo "Hello Jenkins!!"
'''
      }
    }

  }
}
