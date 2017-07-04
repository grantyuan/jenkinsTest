pipeline {
    agent { docker '172.23.21.85:5000/base_node6' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}