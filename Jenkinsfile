pipeline {
	agent any 
	parameters {
      choice choices: ['dev', 'sit', 'pt', 'prod'], description: 'select environment', name: 'ENV'
   
	}
	environment {
      JAVA_HOME = "/usr/bin/java8"
    }

	stages {
		stage("welcome to jenkins") {
			steps {
				script {
					// printing default variables
					println "BUILD_NUMBER ${BUILD_NUMBER}"
					println "WORKSPACE ${WORKSPACE}"
					println "JENKINS_HOME ${JENKINS_HOME}"
					// printing values of parameters
					println "selected env is ${params.ENV}"
					// printing environment variables
					println "my java home path is ${env.JAVA_HOME}"
				}
			}
		}
	}
}
