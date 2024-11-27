
pipeline {
    agent {
       label 'second'
    } 
    stages {
        stage('Build') { 
            steps {
                echo "steps1" 
            }
        }
        stage('Test') { 
            steps {
                 echo "steps1"
            }
        }
        stage('Deploy') { 
            steps {
                echo "steps3"
            }
        }
    }
}