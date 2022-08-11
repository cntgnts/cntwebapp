def f1
pipeline {
  
  agent any 
  
  environment {
  
    name = 'kamal'
    
    }
  
  stages {
    stage('build') {
    
      steps {
        
        echo "${env.name}"

        script {
        f1 = load 'kam.groovy'  
        f1.build(10,20)
        }
      }
    
    }
  }


}
