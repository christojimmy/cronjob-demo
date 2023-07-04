pipeline {
  agent none
  
  stages {
    stage('Pull Image changes 1234') {
      steps {
        script {
          def dockerImage = docker.image('chrizzto/musicshop:latest')
          dockerImage.pull()
        }
      }
    }
  }
}
