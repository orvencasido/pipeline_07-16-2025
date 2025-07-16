pipeline {
    agent any

    environment {
        NAME = "ORVEN"
        LAST_NAME = "CASIDO"
    }

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo "Hello There, $NAME $LAST_NAME"
                '''
            }
        }
        stage('Hello Test') {
            steps {
                sh 'echo "This Worked as a Pipeline!"'
            }
        }
    }
}