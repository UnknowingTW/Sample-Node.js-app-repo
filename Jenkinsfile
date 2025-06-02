@Library('my-shared-lib') _

pipeline {
    agent any

    stages {
        stage('Run Node Pipeline') {
            steps {
                nodePipeline(
                    appDir: '.',  // path to app directory
                    imageName: 'unknowntw/simple-node-app:latest'
                )
            }
        }
    }
}
