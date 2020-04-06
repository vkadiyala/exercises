pipeline{
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "multiple shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}