pipeline {
  agent {
    docker {
      image 'openjdk'
      args '-p 8080:8080'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''cd initial
./gradlew build'''
      }
    }
  }
}