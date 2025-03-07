pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/Ayowumi/Comp367Lab2-Public.git'
      }
    }
    stage('Show Info') {
      steps {
        echo "BUILD_ID = ${env.BUILD_ID}"
      }
    }
  }
}
