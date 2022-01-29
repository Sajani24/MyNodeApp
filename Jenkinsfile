pipeline {
    agent any

    stages {
        stage('LaunchDocker') {
            steps {
                bat 'docker build -t monapp .'
            }
        }
        stage('Run Docker') {
            steps {
                bat 'docker run -p 3000:3000 monapp'
            }
        }
        
    }
}