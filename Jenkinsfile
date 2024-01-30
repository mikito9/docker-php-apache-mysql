pipeline {
  agent {
    // label "docker-agent"
    label "slave1"
  }
  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'sudo docker-compose up -d'
      }
    }
  }
}
