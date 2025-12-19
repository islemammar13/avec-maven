pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World depuis Jenkinsfile'
            }
        }
        stage('Maven') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
