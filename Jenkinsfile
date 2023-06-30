pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/Shmuel790/targil_lesson7.git'
                bat 'python hi.py'
            }
        }
    }
}
