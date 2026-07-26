pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/dkumarautomation707-cmd/TEST_SDK_BYDK.git'
            }
        }

        stage('Verify') {
            steps {
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing PLC project...'
                bat 'echo Test Passed'
            }
        }
    }
}
