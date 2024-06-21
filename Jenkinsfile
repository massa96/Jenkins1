
pipeline{
    agent any

    stages {

      stage{
          parallel{
            stage("Build"){
            steps{
                    echo "Build en cours"
                }
        }
        stage("deploy"){
            steps{
                    echo "deployment  en cours"
                }
        }
        }
      }
        stage("production"){
            steps{
                    echo "Production en cours"
                }
        }
    }
}
