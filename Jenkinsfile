pipeline {
  agent {
    docker {
      image 'maven:3.6.1-jdk-11'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn --version'
        sh 'java --version'
      }
    }
  }
}