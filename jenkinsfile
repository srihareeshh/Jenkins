pipeline{
    agent any
    stages{
        stage('Checkout code'){
            steps{
                git branch: 'main' , url: 'https://github.com/srihareeshh/Jenkins.git'
            }
        }
        stage('Build'){
            steps{
                sh 'python3 sum.py'
            }
        }
    }
}