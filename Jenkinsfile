pipeline {
agent any
  environment {
  name = 'shivu'
}
  stages {
    stage ('BUILD') {
      
      steps {
        echo "This is build"
        echo " name is $name"
      }
    }
    stage ('TEST') {   
      steps {
        echo "This is test"
      }
    }
    stage ('DEPLOY') {
      steps {
        echo "This is deploy"
      }
    }
    
  }
}
