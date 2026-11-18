
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Starting Jenkins CI/CD'
            }
        }

        stage('Environment Check') {
            steps {
                sh 'whoami'
                sh 'java -version'
                sh 'git --version'
                sh 'hostname'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Success') {
            steps {
                echo 'Hello from GitHub + Jenkins!'
                echo 'CI/CD Pipeline completed successfully!'
            }
        }
    }
}
