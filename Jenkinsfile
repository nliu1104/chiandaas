pipeline {
  agent any
  stages {
    stage('package') {
      steps {
        sh 'echo \'hello world\''
      }
    }
    stage('mvn') {
      steps {
        sh 'sh "mvn clean"'
      }
    }
  }
}