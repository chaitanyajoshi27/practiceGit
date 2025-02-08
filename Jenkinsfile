pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: "https://github.com/chaitanyajoshi27/practiceGit.git", branch: 'main'
            }
        }
        stage('Sleep') {
            steps {
                sleep(30)
            }
        }
    }
}