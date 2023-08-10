pipeline {
    agent any
    
    environment {
        MY_VARIABLE = 'Hello, Jenkins!'
    }
    
    stages {
        stage('Display Variable Value') {
            steps {
                script {
                    echo "The value of MY_VARIABLE is: ${env.MY_VARIABLE}"
                }
            }
        }
    }
}
