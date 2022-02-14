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
                sh 'sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 0xB1998361219BD9C9'
                sh 'sudo apt-add-repository "deb http://repos.azul.com/azure-only/zulu/apt stable main"'
                sh 'sudo apt-get -q update'
                sh 'sudo apt-get -y install zulu-8-azure-jdk'
            }
        }
    }
}
