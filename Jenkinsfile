pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the Java source code'
                sh 'javac Hello.java'
                sh 'ls -l'
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