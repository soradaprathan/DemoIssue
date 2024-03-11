pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/soradaprathan/DemoIssue.git', branch: 'main')
      }
    }

    stage('Build') {
      steps {
        
        echo 'Hello from COMP367'
      }
    }

  }
}
