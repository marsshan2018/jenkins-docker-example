pipeline {
    agent {
        node {
            label 'dockeragent' 
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
