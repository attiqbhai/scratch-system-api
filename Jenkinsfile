pipeline {
    agent any
    stages {
        stage('build') {
            sh "mvn clean"
        }
        stage('deploy') {
            sh "mvn package"
        }
    }
}
