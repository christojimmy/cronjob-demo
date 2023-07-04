pipeline {
  agent none
  stages {
    stage('Pull Image') {
      steps {
        script {
          def dockerImage = docker.image('docker pull chrizzto/proapp:latest')
          dockerImage.pull()
        }
      }
    }
  }
}
