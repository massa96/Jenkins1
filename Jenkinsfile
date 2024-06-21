
pipeline{
    agent any

   triggers{
       pollSCM('* * * * *')
   }
    stages {
        stage("Build"){
            input{
                message "Do you want to build the project?"
                ok "Yes"
            }
            steps{
               
                echo "Hello World 1s "
    
                }
        }
    }
}
