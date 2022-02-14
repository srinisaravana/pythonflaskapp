pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'ls'
                sh 'sudo -i'
                sh 'apt-get install -y maven'
            }
        }
    }
}
