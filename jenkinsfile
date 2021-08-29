pipeline{
agent{
label ''
}
stages{
stage('checkout')
{
steps
{
checkout scm
}
}
stage ('Creation of folder')
{
steps
{
sh "cd /home/ubuntu; sudo mkdir testfolder"
}
}
stage ('creation of folder in different server')
{
steps{
node(ansible-server)
}
{
sh "ch home/ubuntu; sudo mkdir differeentserver"
}
}
}
}
