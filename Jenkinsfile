pipeline {
  agent any
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
          println "Job name is ${JOB_NAME}"
		  println "Build id is ${BUILD_ID}"
        }
      }
    }
  }
}
