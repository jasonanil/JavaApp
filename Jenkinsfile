pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'java ./src/Hello.java'
                    } else {
                        bat 'java ./src/Hello.java'
                    }
                }
            }
        }
    }
}
