pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
                echo 'Build Stage'
                sh 'npm install'
          }
      }
      stage('Test'){
          steps{
              echo 'Test Stage'
          }         
      }
        stage('Deploy'){
          steps{
         echo 'Deploy stage'
          }         
      }
        
    }
}
