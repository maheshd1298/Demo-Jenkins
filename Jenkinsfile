pipeline {
    agent any

    stages {
        stage('Number1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Number2') {
            steps {
                sleep 60
            }
        }  // <-- Closing bracket added for stage 'Number2'
        
        stage('Number3') {
            steps {
                echo 'Hello Pune'
            }
        }  // <-- Closing bracket added for stage 'Number3'
    }  // <-- Closing bracket added for stages
}  // <-- Closing bracket added for pipeline
