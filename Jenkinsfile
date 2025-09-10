pipeline {

    agent any // Runs on any available agent
    stages {
        stage('clone') {
            steps {
                
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
