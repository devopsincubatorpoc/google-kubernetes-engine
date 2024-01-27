pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/devopsincubatorpoc/pipelinespoc', branch: 'main', credentialsId: '73f0f829-d2dd-478e-bc77-0a1136155c99')
      }
    }

  }
}