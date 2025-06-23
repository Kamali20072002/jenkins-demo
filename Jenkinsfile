pipeline {
    agent {
        docker {
            image 'python:3.10'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo '✅ Running Build Step'
                sh 'python hello.py'
            }
        }
        stage('Test') {
            steps {
                echo '✅ Running Test Step'
                sh 'echo All tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo '✅ Running Deploy Step'
            }
        }
    }
}
