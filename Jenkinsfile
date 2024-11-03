pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World 2'
            }
        }
        stage('Shell1') {
            steps {
                sh 'ls /etc/netplan'
            }
        }
        stage('Shell2') {
            steps {
                sh 'ls /home/'
            }
        }
    }
}
