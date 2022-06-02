pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
               echo "build stage"
            }
        }
        stage('Test') {
            steps {
                echo 'This is test stage'
            }
        }
        stage('Deliver') { 
            steps {
                echo "deliver stage"
            }
        }
    }
}
