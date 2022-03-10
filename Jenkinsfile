pipeline {
    agent any 
    stages {
        stage('build') { 
            steps {
                sh "cd src/ && javac programme.java"
            }
        }
        stage('run') { 
            steps {
                sh "cd src/ && java programme.java"
            }
        }
        stage('deploy') { 
            steps {
                sh "cd C:/wamp/www/mspr"
            }
        }
    }
}
