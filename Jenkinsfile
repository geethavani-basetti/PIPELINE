pipeline {
  agent any
  stages {
    stage('Development') {
      parallel {
        stage('Development') {
          steps {
            echo 'stage of development'
          }
        }

        stage('Testing') {
          steps {
            echo 'this is testing'
          }
        }

      }
    }

    stage('pulling the code') {
      steps {
        echo 'to git hub'
      }
    }

    stage('building') {
      steps {
        echo 'job creation'
      }
    }

    stage('Deployment') {
      steps {
        echo 'in app server'
      }
    }

  }
}