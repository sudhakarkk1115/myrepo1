def myfn(a=1000,b=2000) {
println "Welcome to functions"
println "my a value is ${a} & my b value is ${b}"
}
pipeline {
  agent any    
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
		myfn()
		myfn(100,200)
		myfn(100)         
		 }
		}
    }
  }
}
