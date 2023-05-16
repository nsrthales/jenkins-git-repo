pipeline {
    agent { docker { image 'maven:3.9.0-eclipse-temurin-11' } }
    agent any

    stages {
        stage('build') {
        stage('Build') {
            steps {
                sh 'mvn --version'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
