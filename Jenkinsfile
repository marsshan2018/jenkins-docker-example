pipeline {
    agent {
        node {
            label 'docker-agent' 
        }
    }
    stages {
        stage('Test') {
            steps {
                echo "Testing.."
                sh 'ls'
            }
        }
        stage('Post Compile') {
            steps {
                echo "Compile completed.."
            }
        }
    }
}
