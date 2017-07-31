pipeline {
  agent {
    dockerfile {
      filename 'DockerFile'
    }
    
  }
  stages {
    stage('package') {
      steps {
        sh 'echo \'hello world\''
      }
    }
    stage('mvn') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}