pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Build Id: ${env.BUILD_ID}, Jenkins Url: ${env.JENKINS_URL}"
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
