pipeline {
    agent any
    stages {
        stage('w/o docker') {
            steps {
                sh '''
                    echo "hello world"
                    ls -la
                    touch container-no.txt
                '''
            }
        }
    }
}