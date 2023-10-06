pipeline {
    agent {
        label 'maven'
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/satty001/twt-trend.git'
            }
        }
    }
}
