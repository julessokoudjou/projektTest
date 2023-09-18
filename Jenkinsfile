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
    }
    
    stages {
        stage('build') {
            steps {
                echo 'node test hat geklapptgkjkjgkjgkjkkj 17:40'
                bat 'mvn clean install'

            }
        }
    }
}
