pipeline {
  stages {
      stage('Clone repository') {               
      steps {       
            checkout scm    
      }
      } 
    stage('Docker-compose up') {
      steps{
        script {
	 docker-compose up -d
        }
      }
    }
}
