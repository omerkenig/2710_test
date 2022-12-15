pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -htr'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python main.py'
            }
        }
    }
}
