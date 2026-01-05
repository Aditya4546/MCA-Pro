pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/USERNAME/REPO_NAME.git',
                    credentialsId: 'github-creds'
            }
        }
    }
}
