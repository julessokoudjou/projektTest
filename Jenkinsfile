pipeline {
    agent any
    tools{
        
        maven 'maven'
    }
    triggers{   
        pollSCM
    }
    
    stages {
        stage('build') {
            steps {
                echo 'node test hat geklappt'

            }
        }
    }
}
