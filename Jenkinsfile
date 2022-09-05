pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/KittiLee/S1.git', branch: 'main')
      }
    }

    stage('Release') {
      steps {
        echo 'Ready to release etc.'
      }
    }

  }
}
