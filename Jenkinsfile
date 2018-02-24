pipeline {
    agent any
    options {
       overrideIndexTriggers(true) 
    }
    stages {
        stage('Example') {
            steps {
                sleep(time: 10, unit: 'SECONDS') 
                echo 'Hello World 2'
            }
        }
    }
}
