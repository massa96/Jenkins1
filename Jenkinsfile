
pipeline{
    agent any

   triggers{
       cron('* * * * *')
   }
    stages {
        stage("Build"){
            steps{
                for(int i=0;i<10;i++){
                    echo "Hello World ${i}"
                }
                }
        }
    }
}
