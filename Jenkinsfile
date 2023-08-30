pipeline {
  agent any
  stages {
    stage("working inside maven pod") {
      steps {
        script{
        a = 20
        if(a == 20){
          println "value of a is ${a}"
        }
        else {
          println "value of a is not equal to 20"
        }
      }
    }  
  }
 }
}
