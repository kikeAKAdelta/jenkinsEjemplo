pipeline{
    agent any
    
    /*triggers{
     cron('H * /4 * * 1-5')   
    }*/
    
    /*tools{
      maven '/opt/apache-maven-3.5.2'   
    }*/
    
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
            
            input {
                message "Should we continue?"
                ok "Yes, we should."
                submitter "alice,bob"
                parameters {
                    string(name: 'PERSONAS', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
            }
            
            options{
                timeout(time:1,unit:'HOURS')   
            }
            
            
            
            steps{
                echo 'Hola perras, ${PERSON}, tal bitch'  
                echo CC
                //sh 'mvn --version'
            }
        }
    }
    
    
}
