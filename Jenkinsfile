pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('Build') { 
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Start building..."
                '''
                cd my-react-app
                npm install
            }
        }
    }
}