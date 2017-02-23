pipeline {
    agent { docker 'openjdk:latest' }
    stages {
        stage('hello') {
            steps {
                sh 'echo hello'
                sh 'echo world'
            }
        }
        stage('world') {
            steps {
                sh 'echo test'
            }
        }
    }
}
