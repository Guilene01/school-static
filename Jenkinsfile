pipeline{
    agent {label 'java'
    }
    stages{
        stage('Test'){
            steps{
                sh 'docker -v'

            }
        }
        stage('Build'){
            steps{
                sh 'docker build -t webapp .'
                
            }
        }
    }
}