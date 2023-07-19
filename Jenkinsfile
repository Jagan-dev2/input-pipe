pipeline{
    agent any
    parameters {
         string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
    stages{
        stage("Build"){            
        steps{
        timeout(time :60,unit : 'SECONDS'){
        input message: "Should we continue",ok : "Yes",submitter: "Mohan"    
              
         }       
           echo "Input success for ${PERSON}"
           }
        }
    }
}
