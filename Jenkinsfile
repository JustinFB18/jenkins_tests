pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'python3 ./main.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'python3 ./suma.py'
                sh 'python3 ./resta.py'
            }
        }
    }
}
