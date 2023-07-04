pipeline {
  agent none
  
  stages {
    stage('Pull Image') {
      steps {
        script {
          def dockerImage = docker.image('chrizzto/musicshop:latest')
          dockerImage.pull()
        }
      }
    }
  }
}
