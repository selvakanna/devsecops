pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'test'
        withSonarQubeEnv 'sonar'
      }
    }
  }
}