pipeline {
    agent any 
    stages {
      stage("build") {
        steps { 
            echo 'building apps ...'
        }
      }
        
          stage ("test") {
              steps {
                  echo 'testing apps ...'
              }
              
          }
          
      
        stage("deploy") {
            steps {
                echo 'deploy apps ...'
            }
        }
   
   
    }
}
