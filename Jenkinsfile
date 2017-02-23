pipeline {
    agent { docker 'openjdk:latest' }
    stages {
        stage('hello') {
            steps {
                sh 'echo hello'
                sh 'echo world'
            }
            steps {
                sh 'echo hello2'
                sh 'echo world2
           }
        }
        stage('world') {
            steps {
                sh 'echo test'
            }
        }
    }
}
