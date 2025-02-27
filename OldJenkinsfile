pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', 
                    url: 'https://github.com/alijarai12/aminil-assignment-1.git', 
                    credentialsId: 'gittoken' 
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
    }
}
