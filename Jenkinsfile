pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/kunal22823/JenkinsExample.git'
            }
        }
        stage('Build') {
            steps {
                bat 'javac Jenkins.java'
            }
        }
        stage('Execute') {
            steps {
                bat 'java Jenkins'
            }
        }
    }
}
