@Library('my-shared-lib') _  

node {
    stage('Use Shared Pipeline') {
        nodePipeline(
            appDir: '.',   
            imageName: 'unknowntw/simple-node-app:latest'
        )
    }
}
