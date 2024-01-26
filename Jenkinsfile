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
        stage("Environment") {
            steps {
                sh "cat Test"
            }
        } 
        stage("Morning wish") {
            steps {
                print("Good morning $name")
            }
        }    
    }
}
