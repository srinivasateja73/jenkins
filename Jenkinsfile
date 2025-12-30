pipeline {
    agent  {
        node {
            label 'agent-1'
        }

    stages {
        stage('Building') {
            steps {
               echo "building"
            }
        }
        stage('Testing') {
            steps {
               echo "testing"
            }
        }
        stage('Deploying') {
            steps {
                echo "deploying"
            }
        }
    }
}