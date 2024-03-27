pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                python3 main.py
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                python3 suma.py
            }
        }
    }
}
