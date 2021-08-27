pipeline {
agent {
label 'ubuntu-slave'
}        
stages {
    
stage ('checkout')
{                
steps 
    {
        checkout scm        
     }
}
 stage ('creation for folder')
 {
   steps
     {
         sh "cd /home/ubuntu ; sudo mkdir caterpiller" 
     }   
 }
     }
    
}
