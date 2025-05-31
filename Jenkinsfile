pipeline {
    agent any

    options {
        skipDefaultCheckout(true)
    }

    stages {
        stage('Start') {
            steps {
                echo 'Step 1: Starting the pipeline...'
                echo 'Step 2: Initial checks...'
            }
        }

        stage('Checkout SCM') {
            steps {
                echo 'Step 1: Logging before checkout...'
                checkout scm
                echo 'Step 2: Finished checkout.'
            }
        }

        stage('Build') {
            steps {
                echo 'Step 1: Cleaning workspace...'
                echo 'Step 2: Building the project... (simulated)'
                echo 'Step 3: Build artifacts created.'
            }
        }

        stage('Test') {
            steps {
                echo 'Step 1: Running unit tests...'
                echo 'Step 2: Checking test coverage...'
            }
        }


        stage('End') {
            steps {
                echo 'Step 1: Pipeline finished successfully.'
                echo 'Step 2: Sending notifications...'
            }
        }
    }
}
