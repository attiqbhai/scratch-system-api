pipeline {
    agent any
    environment {
        mainvar: "main-test-1"
    }
    stages {
        stage('build') {
            environment {
                stagevar: "stage-test-1"
            }
            steps {
                echo mainvar
                echo stagevar
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
