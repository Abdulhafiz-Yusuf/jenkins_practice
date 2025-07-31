pipeline {
    agent any
    environment {
        GITHUB_TOKEN = credentials('github-token')
        DOCKERHUB_USER = credentials('docker-user')
        DOCKER_IMAGE = 'my-docker-image'
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Abdulhafiz-Yusuf/jenkins_practice.git'
            }
        }
        stage('Echo') {
            steps {
                echo '2 Hello from GitHub-triggered pipeline!'
                echo "GITHUB_TOKEN: ${GITHUB_TOKEN}"
                echo "DOCKERHUB_USER: ${DOCKERHUB_USER}"    
                echo "DOCKER_IMAGE: ${DOCKER_IMAGE}"
            }
        }
    }
}
