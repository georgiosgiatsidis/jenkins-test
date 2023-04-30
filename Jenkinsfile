pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }
  }

  stages {
    stage('Hello World') {
      steps {
        sh 'echo "Hello World"'
      }
    }
  }

  post {
    always {
      cleanWs()
    }
  }
}
