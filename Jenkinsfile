def f1
pipeline {
  
  agent any 
  
  environment {
  
    name = 'kamal'
    
    }
  
  stages {
    stage('build') {
    
      steps {
        f1 = load 'kam.groovy'  
        echo "${env.name}"
        f1.build()
      
      }
    
    }
  }


}
