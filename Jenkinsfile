pipeline{
  agent any
  
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