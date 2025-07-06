pipeline { 
    agent {
        docker {
            image 'alpine:latest'
        }
    }

    stages {
        stage('Docker Agent Test') {
            steps {
                echo '🎉 Hello from inside a Docker container!'
                sh 'uname -a'
            }
        }
    }
}
