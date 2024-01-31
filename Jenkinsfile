pipeline {
  agent {
    // label "docker-agent"
    label "slave1"
  }
  stages {
    stage ('Run Docker Compose') {
      steps{
        // sh 'sudo docker-compose up -d'
        // Using 'bat' instead of 'sh' for Windows
        bat 'docker-compose up -d'
      }
    }
  }
}
