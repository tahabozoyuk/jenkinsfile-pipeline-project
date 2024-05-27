pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
        stage('runpython') {
            steps {
                echo 'Running the python code.'
                sh 'python3 pipeline.py'
            }
        }
    }
}