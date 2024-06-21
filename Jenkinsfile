
pipeline{
    agent any
    stages {
        stage("Build"){
            steps{
               
                echo "Hello World 1s je suis en Build "
                }
        }
        stage('deployment en production'){
            when{
                branch 'main'
            }
            steps{
                echo "Hello World 2 je suis en deployment"
                }
        }
    }
}
