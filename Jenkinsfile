pipeline {
    agent any
    stages {
        stage('Docker Build') {
            steps {
                sh './build.sh'
            }
        }
        stage('Deploy Env') {
            steps {
                sh './deploy.sh'
            }
        }
    }
}
