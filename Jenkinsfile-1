pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'feature/sree-practice', url: 'https://github.com/srmanthena83/AR-tweet-trend.git'
            }
        }
    }
}