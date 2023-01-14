pipeline {
 agent any
  stages {
   stage ('this is first stage') {
    steps {
     echo "final request"
     }
    }
    stage ('this is uytufhgfvhghfhgffirst stage') {
    steps {
     echo "final rejguhbquest"
     }
    }
  }
}
