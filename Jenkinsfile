pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                 git branch: 'main',
            url: 'https://github.com/Aditya4546/MCA-Pro.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'pip3 install -r requirements.txt'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'pytest'
            }
        }
    }
}
