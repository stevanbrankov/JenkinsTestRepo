pipeline{
  agent any 
  
  stages{
    stage ('Clean'){
      steps{
       mvn clean 
      }
    }
    stage ('Install'){
         steps{
       mvn install 
      }  
    }
    stage ('Third stage'){
           steps{
       echo 'Hello boyyyy' 
      }
    }
  
  }
}
