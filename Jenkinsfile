pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compileddd the java source code???'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.???'
                sh 'java Hello'
            }
        }
    }
}
