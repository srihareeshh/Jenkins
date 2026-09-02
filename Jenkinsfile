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
                /*
                    using (echo num1 && num2) sends '5' as the first input
                    and '10' as the second input into the python script.
                */
                sh 'python3 sum.py'
            }
        }
    }
}