pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the Java v2 source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled Java code.'
                sh 'java Hello'
            }
        }
    }
}
