
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'startuje budowanie'
                sh 'cp -r kolejny kolejny2'
                sh 'ls -al '
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "zakladam ze to jest tutaj"
                sh 'ls -al '
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


