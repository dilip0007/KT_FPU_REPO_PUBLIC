pipeline {
    agent any
    environment {        
        DOCKERHUB_USERNAME = "dilipnigam007"
          
        }

    stages {
        stage('testing') {
            steps {
                sh "echo hi"
                sh "touch fpu"
                
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
                sh "pwd;ls"
              
                
            }
        }

        stage('deploy') {

            steps {
               
    
                 sh "echo hi"
                 
             
                 
                 
                 
                 
                
                 
                 
                
                
            }

        }   
             

        
    
        
        
    }
}
