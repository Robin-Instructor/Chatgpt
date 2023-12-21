pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Python dosyasını çalıştırmak için bir shell komutu kullanalım.
                sh 'python hello_world.py'
            }
        }
    }

    post {
        success {
            echo 'Uygulama calisti'
        }
        failure {
            echo 'Uygulama basarisiz oldu!'
        }
    }
}
