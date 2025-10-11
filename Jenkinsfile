pipeline {
  agent any

  stages {
    stage('Hello') {
      steps {
        echo 'Hello, Jenkins is working!'
      }
    }

    stage('Build') {
      steps {
        echo 'This is where build commands go.'
        sh 'echo Building project...'
      }
    }

    stage('Test') {
      steps {
        echo 'Running tests...'
        sh 'echo Tests completed successfully.'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment step here.'
      }
    }
  }

  post {
    success {
      echo 'Pipeline completed successfully!'
    }
    failure {
      echo 'Pipeline failed!'
    }
  }
}

