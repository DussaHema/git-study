pipeline {
  agent any
  stages {
    stage("Welcome to world") {
        steps {
          script {
            println "Hi team welcome to devops"
            // User defined variables
            var1 = 20
            println "My var1 value is ${var1}"
            // Predefined variables 
            println "my BUILD_NUMBER is ${BUILD_NUMBER}"
            println "my JOB_NAME is ${JOB_NAME}"
          }
        }
      }
    }
  }
