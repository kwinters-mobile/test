pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building!'
                sh "if [ -f README.md ]; then echo 'file found'; else echo 'README.md file not found'; exit 1; fi "
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}