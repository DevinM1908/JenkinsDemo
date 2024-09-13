pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                echo 'wowww'
                
                script {
                    def test = (2 + 1 > 5) ? 'cool' : 'not cool'
                    echo test
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
