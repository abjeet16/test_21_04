pipeline {
    agent any
    triggers {
        pollSCM('* * * * *')
    }
    stages {
        stage('Checkout') {
            steps {
                sh 'javac random.java'
                sh 'java random.java'
           }
        }
    }
}
