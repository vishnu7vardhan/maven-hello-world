pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                checkout scm
            }
        }
        stage('Compile') {
            steps {
                echo 'I am in compile stage'
            }
        }
        stage('Test') {
            steps {
                echo 'I am in test stage'
            }
        }
    }
}