pipeline{
    agent any
    
    /*triggers{
     cron('H * /4 * * 1-5')   
    }*/
    
    tools{
      maven 'apache-maven-3.0.1'   
    }
    
    parameters{
     string(name:'PERSON',defaultValue:'MR. JENKINS',description:'SOY LA MERA VERGA EN SALSA')   
    }
    
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
                sh 'mvn --version'
            }
        }
    }
    
    
}
