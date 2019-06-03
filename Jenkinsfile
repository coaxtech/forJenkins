Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:2.7.12' } }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
