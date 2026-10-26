pipeline {
    agent any

    stages {
        stage('Checkout Repo') {
            steps {
                checkout scm
                echo 'Repository checkout completed.'
            }
        }

        stage('Run Linter') {
            steps {
                echo 'Running linter...'
                sh 'echo "Linter stage completed."'
            }
        }

        stage('Docker Package') {
            steps {
                echo 'Packaging application with Docker...'
                sh 'docker --version'
            }
        }
    }
}