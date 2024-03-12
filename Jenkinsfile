pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Hello Jenkins"
                input 'Do you approve deployment?'
                echo "approved"
            }
        }
    }
}
