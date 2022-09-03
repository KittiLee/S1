pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/KittiLee/S1/tree/main.git', branch: 'master')
      }
    }

    stage('Release') {
      steps {
        echo 'Ready to release etc.'
      }
    }

  }
}
