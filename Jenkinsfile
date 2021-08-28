pipeline {
    agent any 
    stages {
        stage('clone Respository & clean') { 
            steps {
                sh "rm -rf jenkins-maven"
                sh "git clone https://github.com/san133/devops.git"
                sh "mvn clean -f jenkins-maven"
            }
        }
        stage('Test') { 
            steps {
                sh "mvn test -f jenkins-maven"
            }
        }
        stage('Deploy') { 
            steps {
                sh "mvn package -f jenkins-maven"
            }
        }
    }
}
