pipeline {
	agent any 
	stages {
		stage("welcome to jenkins") {
			steps {
				script {
					var1 =input message: 'enter a value', parameters: [string(defaultValue: '10', name: 'var1 ', trim: true)]
					println "my var1 value is ${var1}"
				}
			}
		}
	}
}


