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
        sh  ' sleep 5 '
      }
    }
    stage ('TEST') {   
      steps {
        echo "This is test"
        sh ' sleep 5'
      }
    }
    stage ('DEPLOY') {
      steps {
        echo "This is deploy"
      }
    }
    
  }
}
