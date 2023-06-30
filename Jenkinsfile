pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python hi.py'
            }
        }
        stage('Hi from new stage') {
            steps {
                bat 'python hi.py'
            }
        }
    }
}
