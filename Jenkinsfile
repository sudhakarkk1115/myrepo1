pipeline {
  agent any
  parameters {
  string description: 'Enter value for \'a\'', name: 'a'
  string description: 'Enter value for \'b\'', name: 'b'
}
   stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
         a=${params.a}
		 b=${params.b}
		 if(a > b){
		 println "a is big"
		 }
		 else {
		 println "b is big"
		 }
        }
      }
    }
  }
}
