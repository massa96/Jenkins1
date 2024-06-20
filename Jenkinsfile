
pipeline{
    agent any
    environnement{
        PATH = "/usr/local/bin:$PATH"
    }
    stages {
        stage("Build"){
            steps{
                echo "BRANCH_NAME : ${env.BRANCH_NAME}"
                echo "BUILD_NUMBER : ${env.BUILD_NUMBER}"
                echo "BUILD_ID : ${env.BUILD_ID}"
                echo "JOB_NAME : ${env.JOB_NAME}"
                echo "WORKSPACE : ${env.WORKSPACE}"
                echo "BRANCH_IS_PRIMARY : ${env.BRANCH_IS_PRIMARY}"
                 echo "PATH : ${env.PATH}"
                }
        }
    }
}