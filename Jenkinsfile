pipeline {
    agent any
    options {
       overrideIndexTriggers(false) 
    }
    stages {
        stage('Example') {
            steps {
                sleep(time: 10, unit: 'SECONDS') 
                echo 'Hello World 1'
            }
        }
    }
}
