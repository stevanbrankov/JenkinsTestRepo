pipeline{
  agent any 
  environment{
    PATH = "/
  }
  stages{
    stage ('Clean install'){
           steps{
             def mvnHome = tool name : 'maven-3', type: 'maven'
             sh " ${mvnHome}/bin/mvn clean install"     
      }
    }
  }
}
