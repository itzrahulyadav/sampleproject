pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/itzrahulyadav/sampleproject', branch: 'main')
      }
    }

    stage('Test') {
      steps {
        sh 'ls -la'
      }
    }

  }
}