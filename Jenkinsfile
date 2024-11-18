pipeline {
    agent any 
    stages {
        stage("Git Checkout") {
            steps{
                
                sh "Git cloning...."
                git changelog: false, credentialsId: 'git-cred', poll: false, url: 'https://github.com/ashishvarshney100/Pipeline1.git'
                
            }
        }
        // stage("Code Compile") {
        //     steps{
        //         sh "Code is Compiling...."
        //     }
        // }
        // stage("Code Build") {
        //     steps{
        //         sh "Code is Building...."
        //     }
        // }
        // stage("Code Test") {
        //     steps{
        //         sh "Code testing is in progress...."
        //     }
        // }
        // stage("Code Deploy") {
        //     steps{
        //         sh "Deploying the application...."
        //     }
        // }
        // stage("Verify Deploy") {
        //     steps{
        //         sh "Verifying the Deployed Application ...."
        //     }
        // }
    }
}