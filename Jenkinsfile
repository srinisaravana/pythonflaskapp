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
                sh 'sudo su'    
                sh 'visudo -f /etc/sudoers'
                'jenkins ALL= NOPASSWD: ALL'


            }
        }
    }
}
