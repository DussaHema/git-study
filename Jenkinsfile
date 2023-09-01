pipeline {
  agent any
  stages {
    stage("working inside maven pod") {
      steps {
        script {
         a = input message: 'Please enter a value ', parameters: [string(defaultValue: '0', name: 'val1', trim: true)]
        
         if(a.tointeger() == 20){
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
