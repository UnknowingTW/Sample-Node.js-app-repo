@Library('my-shared-lib') _  // Name should match Jenkins configuration

node {
    stage('Use Shared Pipeline') {
        nodePipeline(
            appDir: '.', 
            imageName: 'unknowntw/simple-node-app:latest'
        )
    }
}
