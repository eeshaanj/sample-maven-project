pipeline {
  agent any
  tools {
    maven 'MAVEN3'
    jdk 'JAVA8'
    }

  stages {
    stage('Clean') {
       steps {
         sh 'mvn clean'
       }
    }

    stage('Package') {
      steps {
        sh 'mvn package'
      }
    }
  }
}

