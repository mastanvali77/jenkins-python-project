pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/mastanvali77/jenkins-python-project.git'
            }
        }

        stage('Run Python App') {
            steps {
                sh 'python3 app.py'
            }
        }

    }
} 

