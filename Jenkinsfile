pipeline {
  agent {
    docker {
      image 'maven:3.6.1-jdk-11-slim'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'java --version'
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}