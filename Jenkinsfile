pipeline {
    agent any

    stages {
        stage('Check Workspace') {
            steps {
                sh 'pwd'
                sh 'ls -l'
            }
        }

        stage('Run App') {
            steps {
                sh 'python3 version-app/app.py || python3 app.py'
            }
        }
    }
}

