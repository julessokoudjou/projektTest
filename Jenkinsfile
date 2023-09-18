pipeline {
    agent any
    tools{
        
        maven 'maven'
    }
     triggers {
        pollSCM 'H/10 * * * *'
    } 
    
    stages {
        stage('build') {
            steps {
                echo 'node test hat geklappt'

            }
        }
    }
}
