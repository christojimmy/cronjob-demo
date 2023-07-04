pipeline {
  agent none
  
  stages {
    stage('Pull Image') {
      steps {
        script {
          def dockerImage = docker.image('node:16-alpine')
          dockerImage.pull()
        }
      }
    }
  }
}
