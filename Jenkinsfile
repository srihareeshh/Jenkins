pipeline{
    agent any
    stages{
        stage('Checkout code'){
            steps{
                git url:'https://github.com/srihareeshh/Jenkins.git' ,branch : 'main' 
            }
        }
        stage('Build'){
            steps{
                /*
                    using (echo num1 && num2) sends '5' as the first input
                    and '10' as the second input into the python script.
                */
                bat '(echo 5 && echo 10) | python sum.py'
            }
        }
    }
}