def myfn(a,b){
  println "welcome to functions"
  println "my a value is ${a} & my b value is ${b}"
}

pipeline {
  agent any 
  stages {
    stage('Welcome to Jenkins') {
      steps {
        script {
          //calling a function 
          myfn(200,100)
        }
      }
    }
  }
}
