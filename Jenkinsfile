pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Ashaikh609/Ekart_demo.git'
            }
        }
    stage('build application') {
            steps {
                sh "mvn clean package"
            }
        }
        
    }
}