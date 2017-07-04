pipeline {
    agent { docker 'docker pull alpine' }
    stages {
        stage('build') {
            steps {
                sh 'echo hello world'
            }
        }
    }
}