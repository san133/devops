pipeline { 
 agent {
 label 'slave'
 }
 stages {

 stage ('checkout')  
{

 steps 
     {   
           checkout scm 

      }
 }

 stage('Test')
{
      steps {
                sh "cd /home/ubuntu ; sudo mkdir testfloder"
                
            }

}
      }



}
