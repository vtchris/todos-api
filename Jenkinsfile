pipeline {
  agent any
  stages {
    stage('Build Todo API') {
      agent {
        docker {
          image 'maven:3.6.3-adoptopenjdk-8'
        }

      }
      steps {
        sh 'mvn package'
      }
    }

  }
}