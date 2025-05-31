pipeline {
    agent any

    options {
        skipDefaultCheckout(true)
    }

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

        stage('End') {
            steps {
                echo 'Pipeline finished successfully.'
            }
        }
    }
}
