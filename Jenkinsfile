
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'startuje budowanie'
                cp -r kolejny kolejny2
                ls -al 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "zakladam ze to jest tutaj"
                ls -al 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


