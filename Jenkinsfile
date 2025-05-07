pipeline {
    agent any

    stages {
        stage('Klonla') {
            steps {
                echo 'GitHub reposu klonlanıyor...'
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Build işlemi başladı...'
            }
        }
        stage('Test') {
            steps {
                echo 'Test aşaması çalıştı.'
            }
        }
    }
}
