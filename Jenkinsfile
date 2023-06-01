pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("lunemoon769/ci-cd", '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}