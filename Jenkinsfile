pipeline {
  agent any
  stages {
    stage("working with loops") {
      steps {
        script {
         //working with while loops
         a = 1
         while(1<=10){
          println "value of a is ${a}"
          a = a + 1
        }
        //working with for loops 
        for(i=1;i<=10;i++){
          println "value of i is ${i}"
        }
         //working with for loop with list 
         lis1 = [10,20,30]
         for(ele in lis1){
          println "my ele is ${ele}"
         }
       }
     }  
   }
 }
}
