pipeline {
    agent any
    stages {
        stage('Pull Code') {
            steps {
                git 'https://github.com/Abdulhafiz-Yusuf/jenkins_practice.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Pretending to build the app'
            }
        }
        stage('Test') {
            steps {
                echo 'Simulating unit tests'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production (fake)...'
            }
        }
    }
}
