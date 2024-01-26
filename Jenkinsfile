pipeline {
    agent any
    stages {
        stage('checkout'){
            steps{
            echo 'checking out the repo..'
            // accessing the SCM
            }
        }
        stage('build'){
            steps{
            echo 'building...'
            // compiling the application and generating the artifacts(var, jar..)
            }
        }
        stage('test'){
            steps{
            echo 'testing...'
            // validation and unit testing | UAT
        }
        }
        stage('scan'){
            steps{
            echo 'scanning..'
            // scanning for vulnerabilities and other tags
            // sonarqube analysis: SonarCloud
        }}
        stage('quality'){
            steps{
            echo 'quality check!'
            // quality check gateway status and profiles
        }}
        stage('artfactory'){
            steps{
            echo 'pushing to artifactory...'
            // tools like Jfrog, Azure DevOps artifacts
        }}
        stage('deploy'){
            steps{
            echo 'deploying to application'
        }}
    }
}
