pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                git branch:'main',url 'https://github.com/abjeet16/devopsTest1.git'
            }
        }

        stage('Build'){
            steps{
                echo 'Building....'
            }
        }
        
        stage('Test'){
            steps{
                echo 'Testing....'
            }
        }
    }
}
