pipeline {
agent none
  stages {
    stage ('BUILD') {
      agent { label 'c1-node' }
      steps {
        echo "This is build"
      }
    }
    stage ('TEST') {
      agent any;
      steps {
        echo "This is test"
      }
    }
    stage ('DEPLOY') {
      agent { label 'j-node' }
      steps {
        echo "This is deploy"
      }
    }
    
  }
}
