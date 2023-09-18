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
                echo 'node test hat geklapptgkjkjgkjgkjkkj 17:40'
                bat 'mvn clean install'

            }
        }
    }
}
