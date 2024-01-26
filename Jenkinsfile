pipeline {
    agent any,
    stages {
        stage('checkout'){
            echo 'checking out the repo..'
            // accessing the SCM
        }
        stage('build'){
            echo 'building...'
            // compiling the application and generating the artifacts(var, jar..)
        }
        stage('test'){
            echo 'testing...'
            // validation and unit testing | UAT
        }
        stage('scan'){
            echo 'scanning..'
            // scanning for vulnerabilities and other tags
        }
        stage('quality'){
            echo 'quality check!'
            // quality check gateway status and profiles
        }
        stage('artfactory'){
            echo 'pushing to artifactory...'
            // tools like Jfrog, Azure DevOps artifacts
        }
        stage('deploy'){
            echo 'deploying to application'
        }
    }
}