pipeline {
  agent {
    docker {
      image 'openjdk'
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