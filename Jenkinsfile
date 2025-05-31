pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Starting the pipeline...'
            }
        }

        stage('Checkout SCM') {
            steps {
                echo 'Checking out code...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project... (simulated)'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests... (simulated)'
            }
        }

        stage('Deliver') {
            steps {
                echo 'Delivering the application... (simulated)'
            }
        }

        stage('End') {
            steps {
                echo 'Pipeline finished successfully.'
            }
        }
    }
}
