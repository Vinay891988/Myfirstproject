pipeline {
    agent any

    stages {
        stage("user info") {
            steps {
                sh "whoami"
            }
        }
        stage("job info") {
            steps {
            sh    "echo 'My first job running' >firstjob.txt"
            }
        }  
        stage("Maven version") {
            steps {
                sh "cat Test"
            }
        }    
    }
}
