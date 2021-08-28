pipeline {
agent {
label 'ubuntu-slave'
}
stages {
stage("Git checkout")
 {      
  steps
     {
         git credentialsId: 'javahome2' , url: https://github.com/san133/devops.git
         
      }
 }
 stage ('creation of folder')
 {
     steps
     {
         sh "cd/home/ubuntu ; sudo mkdir kathafolder"
     }   
 }
