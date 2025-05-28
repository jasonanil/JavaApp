pipeline {
    agent any

    stages {
        stage('Java Class') {
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

        stage('Java Class 2') {
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