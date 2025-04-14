pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'building'
                echo env.BUILD_NUMBER
            }
        }
   
        stage('TEST') {
            steps {
                echo 'TESTING'
                echo "tHE WORKSPACE IS ${env.WORKSPACE}"
            }
        }
   
        stage('Deploy') {
            steps {
                echo 'Hello World'
                echo "tHE result IS ${currentBuild.currentResult}"
                pyyhon cc.py
            }
        }
   
}}
