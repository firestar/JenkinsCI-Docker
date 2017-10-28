pipeline {
  agent {
    dockerfile {
      filename 'primary/Dockerfile'
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