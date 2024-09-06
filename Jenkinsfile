pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiled the java source code for pull scm'
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
