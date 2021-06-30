pipeline {
    agent any
    stages {
        stage('Clone') {
            checkout scm
        }
        stage('Compile') {
            echo 'I am in compile stage'
        }
        stage('Test') {
            echo 'I am in test stage'
        }
    }
}