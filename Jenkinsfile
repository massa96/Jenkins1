
pipeline {
    agent any

    tools {
        gradle 'gradle8.6'
    }

    stages {
        stage('Build') {
            steps {
                sh 'gradle -v'
            }
        }
    }
}
    
