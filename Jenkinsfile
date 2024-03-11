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
        bat '"mvn -Dmaven.test.failure.ignore=true clean package'
        echo 'Hello from COMP367'
      }
    }

  }
}