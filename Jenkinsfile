pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh "mvn clean"
            }
        }
        stage('deploy') {
            steps {
                sh "mvn package"
            }
        }
    }
}
