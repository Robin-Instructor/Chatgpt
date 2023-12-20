pipeline {
    agent any 

    stages {
      
        stage('Compile Java Code') {
            steps {
                // Compile the Java code
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run Java Program') {
            steps {
                // Run the compiled Java program
                sh 'java HelloWorld'
            }
        }
    }

    post {
        always {
            // Cleanup or post-process steps, if any
        }
    }
}
