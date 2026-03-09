pipeline {
    agent any

    stages {
        stage('Installation Backend (Java)') {
            steps {
                dir('backend') {
                    echo 'Compilation Java...'
                    // sh './gradlew build' 
                }
            }
        }

        stage('Unit Tests') {
            steps {
                echo 'Check tests'
                // sh './gradlew test'
            }
        }
    }
}
