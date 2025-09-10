pipeline {

    agent any // Runs on any available agent
    stages {
        stage('clone') {
            steps {
                git branch: 'main', credentialsId: 'c5328a29-9a8d-4d6b-96af-dc33e87ea52a', url: 'https://github.com/Vaidehi1205/exp3.git'
            }
        }

        stage('compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('run') {
            steps {
                bat 'java HelloWorld'
            }
        }

    }
}
