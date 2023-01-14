pipeline {
 agent any
  stages {
   stage ('this is first stage') {
    steps {
     echo "final request"
     }
    }
   }
  }
