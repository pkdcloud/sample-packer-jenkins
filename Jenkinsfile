
pipeline {
    agent { docker { image 'hashicorp/packer:latest' } }
    stages {
        stage('---:build: packer ami    ') {
            steps {
                sh 'packer --version'
            }
        }
    }
}

