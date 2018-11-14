pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/aminefzi/test.git', branch: 'mster')
      }
    }
  }
}