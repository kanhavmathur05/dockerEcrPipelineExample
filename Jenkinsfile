pipeline {
    agent any

    // tools {
    //     // Install the Maven version configured as "M3" and add it to the path.
    //     maven "M3"
    // }

    stages {
        stage('Build') {
            steps {
                // checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/kanhavmathur05/dockerEcrPipelineExample']]])
            echo "Building the application!!"
                
            }
        }
        stage('Test') {
            steps {
                // checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/kanhavmathur05/dockerEcrPipelineExample']]])
            echo "Testing the application!!"
                
            }
        }
        stage('Deploy') {
            steps {
                // checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/kanhavmathur05/dockerEcrPipelineExample']]])
            echo "Deploying the application!!"
                
            }
        }
    }
}
