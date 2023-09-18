pipeline {
    agent any
    tools{
        
        maven 'maven'
    }
     triggers {
        pollSCM '* * * * *'
    } 

    stages {
        stage('checkout') {
            steps {
            checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/julessokoudjou/projektTest.git']]) 

            }
        }

        stage('build') {
            steps {
                echo 'node test hat geklapptgkjkjgkjgkjkkj 17:40'
                sh 'mvn clean install'

            }
        }
    }
}
