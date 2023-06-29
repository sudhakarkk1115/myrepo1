def myfn(a,b) {
println "Welcome to functions"
println "my a value is ${a} & my b value is ${b}"
}
pipeline {
  agent any    
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
		myfn(100,200)
         
		 }
		}
    }
  }
}
