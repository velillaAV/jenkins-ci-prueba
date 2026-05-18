pipeline {
    agent any

    stages {

        stage('Clonar') {
            steps {
                echo 'Clonando repositorio...'
            }
        }

        stage('Build') {
            steps {
                echo 'Compilando proyecto...'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Desplegando aplicación...'
            }
        }
    }
}
