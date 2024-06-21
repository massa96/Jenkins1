
pipeline{
    agent any
    stages {
        stage("Build"){
            when {
                branch  'main'
            }
            steps{
               
                echo " branch ${env.BRANCH_NAME}"
                }
        }
    }
}
