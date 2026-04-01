pipeline {

    agent any

    stages{

        stage('build') {

            steps {
                echo 'This pipeline script is triggered by github webhook'
                sh 'echo integrating jenkins pipeline with github webhook'
                sh 'pwd'
                sh 'whoami'
                sh 'ls'
            }

        }

    }
}