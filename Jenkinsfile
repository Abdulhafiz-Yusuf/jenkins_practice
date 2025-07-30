pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Abdulhafiz-Yusuf/jenkins_practice.git'
            }
        }
        stage('Echo') {
            steps {
                echo 'Hello from GitHub-triggered pipeline!'
            }
        }
    }
}
