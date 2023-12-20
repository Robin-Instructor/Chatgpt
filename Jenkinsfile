pipeline {
    agent any 

    stages {
       

        stage('Build and Run') {
            steps {
                // Execute the Python script
                sh 'python hello.py'
            }
        }
    }

    post {
        always {
            // Cleanup or post-process steps, if any
        }
    }
}
