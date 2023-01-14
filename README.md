pipeline {
 agent 
  stages {
   stage ('this is first stage') {
    steps {
     echo "final request"
     }
    }
  stage {
   steps ('second stage') {
    echo "final check"
    }
   }
  }
}
