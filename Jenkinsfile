pipeline {
    agent {
        label 'docker-slave01'
    }
    stages {
        stage('Checkout') {
            step {
                echo "This is checkout step."
            }
        }
        stage('Build') {
            step {
                echo "This is build step."
            }
        }
        stage('Finish') {
            step {
                echo "Finish all pipeline"
            }
        }
    }
}
