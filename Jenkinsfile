pipeline {
    agent {
        docker {
            image 'alpine:latest'
        }
    }
    stages {
        stage('Docker Agent Test') {
            steps {
                echo '🔍 Inside Docker container'
                sh 'cat /etc/os-release'
                sh 'hostname'
                sh 'ps -eaf | grep "PID TTY"'
            }
        }
    }
}
