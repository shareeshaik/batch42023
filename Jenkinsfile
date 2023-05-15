def myfn(a=200,b=300){
 println "welcome to functions"
 println "my value is ${a} & my value is ${b}"
 }

 pipeline {
	agent any 
	stages {
		stage("welcome to jenkins") {
			steps {
				script {
					//calling a function
					myfn()
					myfn(20,30)
					myfn(20)
					}
					}
				}
			}
		}
		 
