pipeline {
  agent any
  parameters {
  choice choices: ['dev', 'test', 'prod'], description: 'Select Environment', name: 'ENV'
}

  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
          println "Job name is ${JOB_NAME}"
		  println "Build id is ${BUILD_ID}"
		  println "Selected Environment is ${params.ENV}"
        }
      }
    }
  }
}
