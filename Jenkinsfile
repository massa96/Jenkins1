
pipeline{
    agent any

    parameters{
        string(name: 'NAME', defaultValue: 'main', description: 'Branch to build')
        text(name: 'COMMIT_MESSAGE',defaultValue: 'Automated build', description: 'Commit message')
        booleanParam(name: 'PUSH_CHANGES',defaultValue: true,description: 'Push changes to remote repository')
        choice(name: 'BUILD_TYPE',choices: ['Debug', 'Release'],description: 'Build type')
        password(name: 'GITHUB_TOKEN',defaultValue: '',description: 'GitHub token for authentication')
    }
    stages {
        stage("Build"){
            steps{
                echo "string : ${NAME}"
                echo "text : ${COMMIT_MESSAGE}"
                echo "booleanParam : ${PUSH_CHANGES}"
                echo "choice : ${BUILD_TYPE}"
                echo "password : ${GITHUB_TOKEN}"

                }
        }
    }
}