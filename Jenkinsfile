pipeline {
  agent any
    
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
         for {i=1;i<10;i++}
		 println "My i value is ${i}"
		 i=1
		 while (i<=10) {
		 println "My i value is ${i}"
		 i=i+1
		 }
		 }
		}
    }
  }
}
