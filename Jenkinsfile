pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World"'
                bat '''
                    echo "Multi-line shell steps works too"
                    dir
                '''
            }
        }
    }
}
