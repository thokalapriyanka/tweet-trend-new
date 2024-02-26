pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', credentialsId: 'Git-cred', url: 'https://github.com/thokalapriyanka/tweet-trend-new.git'
            }
        }
    }
}
