pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/dkumarautomation707-cmd/TEST_SDK_BYDK.git'
            }
        }

        stage('List Files') {
            steps {
                bat 'dir'
            }
        }
    }
}
