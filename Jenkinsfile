pipeline {
  agent any
  stages {
    stage ('Smoke Test') {
      steps {
        sh 'chmod +x ./smoke-google'
        sh './smoke-google'
      }
    }
  }
}
