pipeline {
agent {
label 'ubuntu-slave'
}
stages {
stage("Git checkout")
 {      
  steps
     {
         checkout scm
         
      }
 }
 stage ('creation of folder')
 {
     steps
     {
         sh "cd/home/ubuntu ; sudo mkdir kathafolder"
     }   
 }
