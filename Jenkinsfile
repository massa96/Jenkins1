
pipeline{
    agent any

    stages {

      stage("Build"){
        matrix{
            axes {
                    axis 
                    {
                        name 'PLATFORM' 
                        values 'Windows', 'Linux', 'Mac'
                    }
                    axis{
                         name 'ARCH'
                        values 'x86', 'x64','x32'
                        }
                }
        stage("Build and Test"){
                steps{
                    echo "Building and testing on ${PLATFORM} ${ARCH}"
                }
        }
        stage("Production") 
        {
            steps {
                echo "Deploying to production on ${PLATFORM} ${ARCH}"
                // Add your deployment commands here
                }
        }
        }

      }
    }

    
}
