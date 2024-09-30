pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'docker start contenedor_mysql'
                    sh 'echo prueba en vivo de jenkins'
                }
            }
        }
    }
}
