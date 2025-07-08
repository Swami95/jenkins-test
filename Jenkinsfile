pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/Swami95/jenkins-test'
      }
    }

    stage('Build') {
      steps {
        echo "Build Success"  // Replace with your actual build command
      }
    }

    stage('Test') {
      steps {
        echo "Test Success"   // Replace with your test command
      }
    }
  }
}
