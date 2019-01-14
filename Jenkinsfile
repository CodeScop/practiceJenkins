pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building this first.'
        sh 'date'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing it second.'
        sh 'whoami'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying it third.'
        echo 'it done'
      }
    }
  }
}