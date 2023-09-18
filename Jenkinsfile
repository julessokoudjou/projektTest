pipeline {
    agent any
    tools{
        
        maven 'maven'
    }
     triggers {
        pollSCM '* * * * *'
    } 
    
    stages {
        stage('build') {
            steps {
                echo 'node test hat geklapptgkjkjgkjgkjkkj 14:50'
                bat 'mvn clean install'

            }
        }
    }
}
