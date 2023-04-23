pipeline {
    agent{
        docker { image 'python:3.10'}
    }

    stages{
        stage("task"){
            steps{
                sh 'python main.py'
            }
        }
    }
}