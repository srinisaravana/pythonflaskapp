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
                sh 'echo "jenkins ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers'    
                sh 'cat /etc/sudoers'
               }
        }
    }
}
