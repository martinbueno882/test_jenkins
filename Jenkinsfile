pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'docker pull mysql:latest'
                    sh 'docker run --name contenedor_mysql -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=bd_test -e MYSQL_USER=user -e MYSQL_PASSWORD=mi_contrasenia -p 3306:3306 -d mysql:latest'
                    sh 'inicio el docker'
                }
            }
        }
    }
}
