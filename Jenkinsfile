pipeline {
  agent none
  
  stages {
    stage('Pull Image') {
      steps {
        script {
          def dockerImage = docker.image('docker pull chrizzto/petshop:latest')
          dockerImage.pull()
        }
      }
    }
  }
}
