pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Unal Kandan herkese merhaba'
                echo 'Bu basit bir Pipeline-webhook projesidir'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}