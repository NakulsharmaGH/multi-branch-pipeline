pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'new', url: 'https://github.com/NakulsharmaGH/helloworldpipeline.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 helloworld.py'
            }
        }
    }
}
