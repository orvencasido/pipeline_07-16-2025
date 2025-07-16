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
    }
}