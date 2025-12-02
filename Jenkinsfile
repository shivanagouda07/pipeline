pipeline {
agent none
  stages {
    stage ('BUILD') {
      agent any;
      steps {
        echo "This is build"
      }
    }
    stage ('TEST') {
      agent { label 'j-node' }
      steps {
        echo "This is test"
      }
    }
    stage ('DEPLOY') {
      agent { label 'c1-node' }
      steps {
        echo "This is deploy"
      }
    }
    
  }
}
