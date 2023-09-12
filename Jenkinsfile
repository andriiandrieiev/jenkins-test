pipeline {
    agent any

    stages {
        stage('Capture Current Time') {
            steps {
                script {
                    def timestamp = new Date().format('dd-MM-yyyy')
                    echo "Current Time (Formatted): ${timestamp}"
                }
            }
        }

        // Add more stages as needed
    }
}
