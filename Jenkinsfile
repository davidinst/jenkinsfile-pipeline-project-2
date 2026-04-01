pipeline {

    agent any

    stages{

        stage('build') {
            steps {
                echo 'compiling the source code'
                sh 'javac Hello.java'
                sh 'ls'

            }
        }

        stage('run') {
            steps {
                echo 'Running the app'
                sh 'java Hello'
            }
        }

    }
}