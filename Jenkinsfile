pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-p 3000:3000' 
        }
    }
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