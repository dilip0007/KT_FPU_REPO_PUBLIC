pipeline {
    agent any
    environment {        
        DOCKERHUB_USERNAME = "dilipnigam007"
          
        }

    stages {
        stage('Build') {
            steps {
                sh "echo hi"
                
            }
        }
        stage('Push Docker Image'){
            steps {
                 withCredentials([usernamePassword(credentialsId: 'dockerhub', passwordVariable: 'pass', usernameVariable: 'user')]) {
                
                     sh "ls -lrt"
                     
                     
                 }
            }
        }

        stage('Delete Docker Images'){
            steps {
                sh "pwd"
              
                
            }
        }

        stage('deploy') {

            steps {
               
    
                 sh "echo hi"
                 
             
                 
                 
                 
                 
                
                 
                 
                
                
            }

        }   
             

        
    
        
        
    }
}
