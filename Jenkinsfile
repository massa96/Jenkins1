
pipeline {
    agent any

    tools {
        gradle 'gradle8.9'
    }

    stages {
        stage('Build') {
            steps {
                sh 'gradle -v'
            }
        }
    }
}
    
