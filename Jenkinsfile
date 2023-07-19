pipeline{
    agent any
    stages{
        stage("Build"){
        steps{
         timeout(time :60,unit : 'SECONDS')
            input {
                message "Should we continue"
                ok "Yes"
                submitter "Mohan"
            }
        
           echo "Input option"
        }
        }
    }
}
