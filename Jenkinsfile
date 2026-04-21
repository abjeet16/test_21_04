pipeline {
    agent any
    triggers {
        //pollSCM('* * * * *')
        cron('* * * * *')
    }
    stages {
        stage('Checkout') {
            steps {
                sh 'javac random.java'
                sh 'java random'
           }
        }
    }
}
