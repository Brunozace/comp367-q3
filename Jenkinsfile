pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Show Variables') {
            steps {
                bat 'echo JENKINS_URL=%JENKINS_URL%'
                bat 'echo BUILD_ID=%BUILD_ID%'
            }
        }
    }
}
