pipeline {
  agent any
  parameters {
  choice choices: ['dev', 'test', 'prod'], description: 'Select Environment', name: 'ENV'
}
  environment {
  JAVA_HOME = "/usr/bin/java8"
}
  stages {
    stage ("Welcome to Jenkins") {
      steps {
        script {
          println "Job name is ${JOB_NAME}"
		  println "Build id is ${BUILD_ID}"
		  println "Selected Environment is ${params.ENV}"
		  println "My java path is ${env.JAVA_HOME}"
        }
      }
    }
  }
}
