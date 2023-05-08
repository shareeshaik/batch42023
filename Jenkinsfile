pipeline {
  agent any
  parameters {
    choice choices: ['dev', 'sit', 'pt', 'prod'], description: 'Select environment', name: 'ENV'
  }

  stages {
    stage('Welcome to Jenkins') {
      steps {
        script {
          // Printing default variables
          println "BUILD_NUMBER is ${BUILD_NUMBER}"
          println "WORKSPACE is ${WORKSPACE}"

          // Printing values of parameters
          println "Selected env is ${params.ENV}"
        }
      }
    }
  }
}
