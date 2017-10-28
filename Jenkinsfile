pipeline {
  agent {
    dockerfile {
      filename 'slave/Dockerfile'
    }
    
  }
  stages {
    stage('Stage') {
      steps {
        sh 'npm install'
      }
    }
  }
}
