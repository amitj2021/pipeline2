pipeline {
    agent any
    
    stages {
        stage ('Clone Repo') {
            steps {
            checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/amitj2021/gitclone-jenkins.git']])
            }
            }
        stage ('check files') {
            steps {
                sh 'ls -la'
            }
        }
    
