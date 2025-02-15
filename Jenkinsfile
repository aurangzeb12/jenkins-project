pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World 22'
            }
        }

        stage{'New Stage'} {
            steps {
                echo 'Hello Stage 2'
                sh "date"
            }
        }
    }
}