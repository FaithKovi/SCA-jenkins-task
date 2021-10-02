pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pip install requirements.txt'
            }
        }
        stage('test') {
            steps {
                sh 'python3 hello.test.py'
            }
        }
    }
}





