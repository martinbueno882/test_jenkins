pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    docker.image('ubuntu:latest').inside {
                        sh 'echo "Hello from inside a Docker container!"'
                    }
                }
            }
        }
    }
}
