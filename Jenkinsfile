pipeline {
    agent any
  stages {
      stage('Clone repository') {               
      steps {       
            checkout scm    
      }
      } 
    stage('Docker-compose up') {
      steps{
          script{
        sh "docker-compose up -d"
          }
      }
    }
}
}
