
pipeline {
    agent any

    tools {
        gradle 'gradle8.9'
        nodejs 'nodejs22'
    }

    stages {
        stage('Build') {
            steps {
                sh 'gradle -v'
                sh 'node -v'
            }
        }
    }
}
    
