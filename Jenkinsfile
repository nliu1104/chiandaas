pipeline {
  agent {
    docker {
      image 'maven:3.3.3'
    }
    
  }
  stages {
    stage('package') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}