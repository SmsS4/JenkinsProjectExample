pipeline {
    agent any
    tools {nodejs "NodeJS"}
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