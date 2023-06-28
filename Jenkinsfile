pipeline {
  agent any
    parameters {
  	string defaultValue: '0', description: 'Enter Value for a', name: 'a'
	string defaultValue: '0', description: 'Enter Value for b', name: 'b'
}
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
         a=${params.a}
		 b=${params.b}
		 println "value of a is ${params.a}"
		 println "value of b is ${params.b}"
		 }
		}
    }
  }
}
