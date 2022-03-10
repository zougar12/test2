pipeline {
    agent any 
    stages {
        stage('build') { 
            steps {
                sh "cd src/ && javac Programme.java"
            }
        }
        stage('run') { 
            steps {
                sh "cd src/ && java Programme"
            }
        }
        stage('deploy') { 
            steps {
                sh "cd C:/wamp/www/mspr"
            }
        }
    }
}
