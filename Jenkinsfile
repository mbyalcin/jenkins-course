pipeline {
    agent any
    stages {
        stage('First Stage | Build') {
            steps {
                sh 'echo "Build number: ${env.BUILD_NUMBER}"'
                sh 'date > date.txt'
            }
        }
    }
}

