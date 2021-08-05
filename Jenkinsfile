pipeline{
  agent any 

  stages{
    stage ('Clean install'){
         
             def mvnHome = tool name : 'maven-3', type: 'maven'
             sh " ${mvnHome}/bin/mvn clean install"     
      
    }
  }
}
