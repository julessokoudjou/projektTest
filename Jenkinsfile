pipeline {
    agent any
    tools{
        
        maven 'maven'
    }
     triggers {
        pollSCM 'H/1 * * * *'
    } 
    
    stages {
        stage('build') {
            steps {
                echo 'node test hat geklapptgkjkjgkjgkjkkj 14:50'
                sh 'mvn clean install'

            }
        }
    }
}
