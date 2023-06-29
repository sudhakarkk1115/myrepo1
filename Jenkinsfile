pipeline {
  agent any
    
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
         //reading lines from file
		 file myfile = new File("/tmp/test.txt")
		 lines = myfile.readLines()
		 //printing all lines
		 println lines
		 //printing each lines
		 for(line in lines) {
		 println line 
		 }
		 }
		}
    }
  }
}
