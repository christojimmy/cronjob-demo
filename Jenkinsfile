pipeline {
  agent none
  
  stages {
    stage('Pull Image changes') {
      steps {
        script {
          def dockerImage = docker.image('chrizzto/musicshop:latest')
          dockerImage.pull()
        }
      }
    }
  }
}
