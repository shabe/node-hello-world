node {
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'git@github.com:shabe/node-hello-world.git']]])
}


pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }

        stage('Deploy DEV') {
            steps {
                echo 'Deploying....'
            }

        stage('Deploy STAGING') {
            steps {
                echo 'Deploying....'
            }

        stage('Deploy PRODUCTION') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
