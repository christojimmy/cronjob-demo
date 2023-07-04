pipeline {
  agent none
  
  triggers {
    pollSCM('* * * * *')
  }
  
  stages {
    stage('Pull Image') {
      steps {
        script {
          def dockerImage = docker.image('chrizzto/petshop:latest')
          // No need to explicitly pull the image, as it will be done automatically
        }
      }
    }
  }
}
