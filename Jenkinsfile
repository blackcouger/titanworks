pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/blackcouger/titanworks.git', branch: 'main')
      }
    }

    stage('stage1') {
      steps {
        echo 'This is build $BUILD_NUMBER of demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}