pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                node --version
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Start building..."
                '''
                npm install
            }
        }
    }
}