pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("Lunemoon769/CI-CD", '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}