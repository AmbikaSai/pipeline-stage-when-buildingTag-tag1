pipeline{
    agent any
    
    stages{
        stage('Build'){
                  
                      when{
                              tag "2.0"
                      }
                      
                      
           steps{
               echo 'Hello world building tag'
           }
        }
     }
 }
