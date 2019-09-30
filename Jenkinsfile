Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'hasicorp/packer:latest' } }
    stages {
        stage('---:build: packer ami    ') {
            steps {
                sh 'packer --version'
            }
        }
    }
}s