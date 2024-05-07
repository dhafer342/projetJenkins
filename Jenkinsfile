pipeline{
  agent any
  
  environment {
    MY_VAR = 'une variable'
  }

  stages {
    stage('build'){
        steps{
            echo "BRANCH_NAME ${ env.BRANCH_NAME }"
            echo "MY_VAR ${ env.MY_VAR }"
            sh 'printenv'
        }
        
    }
   
  }  
}