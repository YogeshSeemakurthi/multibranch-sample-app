pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
            }
        }
        stage('fixbranch'){
            when{
                branch "fix-*"
            }
            steps {
                sh 'cat README.md'
            }
        }
    }
}
