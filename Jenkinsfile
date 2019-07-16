pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        sh '''chmod +x gradlew
./gradlew assembleDebug'''
      }
    }
  }
}