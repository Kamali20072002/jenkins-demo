pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running Build Step'
                sh 'python3 hello.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Test Step (Placeholder)'
                sh 'echo All tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Running Deploy Step (Simulated)'
            }
        }
    }
}
