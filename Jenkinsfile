pipeline {
agent {
  label 'master'
}
  stages{
    
    stage('Checkout')
    {
      steps
      {
        
          checkout scm
          
      }
    }
    stage('build')
    {
      steps
      {
        sh "cd /var/lib/jenkins/workspace/mypetclinic ; mvn package
  }
    }
  }
}
