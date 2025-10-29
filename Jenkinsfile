pipeline {
    agent any
    stages{
        stage('CodeScan'){
            steps{
                sh 'echo "clone"'
            }
        }
    }
    stage('test'){
        steps{
            sh 'echo "test"'
        }
    }
    stage('createfile'){
        steps{
            sh 'touch test-$BUILD_ID'
        }
    }
}