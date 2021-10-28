pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                echo 'build test'
                sh 'python --version'
                sh 'pip install flask pytest'
                sh 'export pythonpath=src;pytest'
            }
        }
    }
}
