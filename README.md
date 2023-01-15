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
    stage (fjvnfkjdnvksdbfvkdnfkv){
     steps ('second step'){
      echo "thia is final step of the pipw line"
      }
     }
  }
}
