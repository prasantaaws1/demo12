pipeline{

agent any
tools {
jdk 'java11'
maven 'maven3'
}

stages{

stage("Clean workspace"){
steps{
  cleanWs()
    }
   }     

stage("SCM Checkout"){
steps{
    git branch : master, credentialsId: 'github', url: 'https://github.com/prasantaaws1/demo12.git'
    }
   }   
   }

}
