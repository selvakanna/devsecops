pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'test'
        sh '''sonar-scanner \\
  -Dsonar.projectKey=test \\
  -Dsonar.sources=. \\
  -Dsonar.host.url=http://ec2-18-223-205-53.us-east-2.compute.amazonaws.com:9000 \\
  -Dsonar.login=89bb5ae39128d71ae097cdf7c9ad82117337ee74'''
      }
    }
  }
}