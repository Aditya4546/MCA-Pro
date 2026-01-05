pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Aditya4546/MCA-Pro.git',
                    credentialsId: 'github-creds'
            }
        }
    }
}
