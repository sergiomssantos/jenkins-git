pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello New World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
