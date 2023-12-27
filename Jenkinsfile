pipeline {

    parameters {
        booleanParam(name: 'autoApprove', defaultValue: false, description: 'Automatically run apply after generating plan?')
    } 


   agent  any
    stages {
        stage('checkout') {
            steps {
                 script{
                        dir("terraform")
                        {
                            git "https://github.com/pcnguyen2010/example2.git"
                        }
                    }
                }
            }

    
        
    }

  }
