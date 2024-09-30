pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'docker pull mysql:latest'
                    sh 'docker start contenedor_mysql'
                    sh 'echo Prueba de pipeline jenkins'
                    sh 'echo Prueba de pipeline jenkins x2'
                }
            }
        }
    }
}
