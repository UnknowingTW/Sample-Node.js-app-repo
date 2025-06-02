@Library('my-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Run Node Pipeline') {
            steps {
                nodePipeline(
                    appDir: '.',  // or '.' if app files are at root
                    imageName: 'unknowntw/simple-node-app:latest'
                )
            }
        }
    }
}
