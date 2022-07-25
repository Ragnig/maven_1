pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
            stage('Directory') {
            steps {
                sh 'rm -rf test'
                sh 'mkdir test'
            }
        }
    }
}
