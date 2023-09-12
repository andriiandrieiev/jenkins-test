pipeline {
    agent any

    stages {
        stage('Capture Current Time') {
            steps {
                script {
                    def currentTime = new Date()
                    def formattedTime = new SimpleDateFormat("yyyyMMddHHmmss").format(currentTime)
                    echo "Current Time (Formatted): ${formattedTime}"
                }
            }
        }

        // Add more stages as needed
    }
}
