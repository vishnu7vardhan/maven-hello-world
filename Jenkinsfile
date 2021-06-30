pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                checkout scm
            }
        }
        stage('Compile') {
            when {
                branch "main"
            }
            steps {
                echo 'I am in compile stage'
            }
        }
        stage('Unit Test') {
            steps {
                echo 'I am in test stage'
            }
        }
        stage('Test') {
            steps {
                echo 'I am in test stage'
            }
        }
    }
}
