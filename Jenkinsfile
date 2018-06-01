pipeline{
    agent any
    environment{
        CC='clang'
    }
    stages{
        stage('example'){
            
            environment{
              AN_ACCESS_KEY = credentials('my-prefined-secret-text')    
            }
            
            steps{
             echo 'Hola perras'   
            }
        }
    }
    
    
}

