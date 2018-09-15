// Testing
pipeline {
    agent {
        label 'docker-slave01'
    }
    stages {
        stage('Checkout') {
            steps {
                echo "This is checkout step."
                sh 'pwd'
                sh 'ls -la'
            }
        }
        stage('Build') {
            steps {
                echo "This is build step."
            }
        }
        stage('Finish') {
            steps {
                echo "Finish all pipeline"
            }
        }
    }
}
