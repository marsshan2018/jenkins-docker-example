pipeline {
    agent {
        node {
            label 'agent' 
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
                echo "Compile completed..Get a coffee!"
            }
        }
    }
}
