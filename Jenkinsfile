pipeline {
  agent any
  parameters {
  choice choices: ['dev', 'pt', 'uat'], description: 'select the parameter', name: 'ENV'
  string defaultValue: '0.0.0', description: 'Provided the version', name: 'VERSION'
}
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
            //accessing value from parameter
            println "my selected env is ${params.env}"
            println "my selected version is ${params.version}"
          }
        }
      }
    }
  }
