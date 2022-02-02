pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Test"
                    echo "pass2"
                    ls -lah
                '''
            }
        }
    }
}
