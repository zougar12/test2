pipeline {
    agent any 
    stages {
        stage('clone') { 
            steps {
                sh "rm -rf *"
                sh "git clone https://github.com/zougar12/test2"
            }
        }
        stage('build') { 
            steps {
                sh "cd src && javac programme.java"
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
