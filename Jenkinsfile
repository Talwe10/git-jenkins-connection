properties([pipelineTriggers([cron('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls
                python3 hi.py
                '''
            }
        }
    }
}
