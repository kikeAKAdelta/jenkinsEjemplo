pipeline{
    agent any
    
    options{
     timeout(time:1,unit:'HOURS')   
    }
    
    environment{
        CC='clang'
    }
    stages{
        stage('example'){
            
            options{
     timeout(time:1,unit:'HOURS')   
    }
            
            steps{
             echo 'Hola perras'  
                echo CC
            }
        }
    }
    
    
}
