pipeline{
  agent any

  triggers{
   pollSCM('15 * * * *')
  }
  
  parameters {
   string(name: 'NAME',defaultValue:'test', description: ' test description')
  }
  
  
  stages {
     stage('build'){
        steps{
           echo "name : ${NAME}"
        }
     }
  }
  
}