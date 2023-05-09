def myfn(){
  println "welcome to functions"
}

pipeline {
  agent any 
  stages {
    stage('Welcome to Jenkins') {
      steps {
        script {
          //calling a function 
          myfn()
        }
      }
    }
  }
}
