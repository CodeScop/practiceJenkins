pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building this first.'
        sh 'echo date'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing it second.'
        echo 'date'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying it third.'
        echo 'date'
      }
    }
  }
}