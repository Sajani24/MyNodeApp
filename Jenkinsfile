pipeline {
    agent any

    stages {
        stage('LaunchDocker') {
            steps {
                bat 'docker build -t monapp .'
            }
        }
    }
}