pipeline {
    agent any
    stages {
        stage('Verificar Webhook y Clonar') {
            steps {
                echo '¡Webhook exitoso! El pipeline se ejecutó automáticamente.'
                checkout scm 
            }
        }
    }
}
