pipeline {
    agent any

   
    stages {
       
        stage('Build') {
            steps {
                // Java dosyasını derleyin.
                sh 'javac HelloChatGPT.java'
            }
        }

        stage('Run') {
            steps {
                // Derlenmiş Java sınıfını çalıştırın.
                sh 'java HelloChatGPT'
            }
        }
    }

    post {
        success {
            echo 'Uygulama başariyla çalisti!'
        }
        failure {
            echo 'Uygulama başarisiz oldu!'
        }
    }
}
