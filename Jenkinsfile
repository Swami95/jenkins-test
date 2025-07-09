pipeline {
  agent any

    stage('Setup') {
      steps {
        echo 'Installing Python dependencies...'
        sh 'pip3 install -r requirements.txt'
      }
    }

    stage('Build') {
      steps {
        echo 'Build Success - (you can add build commands here if needed)'
      }
    }

    stage('Test') {
      steps {
        echo 'Running main.py...'
        sh 'python3 main.py'
        echo 'Test Success'
      }
    }
  }

  post {
    always {
      echo 'Pipeline finished.'
    }
  }
}
