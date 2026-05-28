pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Webhook працює'
            }
        }

        stage('Git Info') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'git branch'
            }
        }
    }
}