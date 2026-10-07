pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh '''
                rm -rf /opt/project/*
                cp -r * /opt/project/
                '''
            }
        }
    }
}
