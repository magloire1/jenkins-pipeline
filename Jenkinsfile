pipeline {
    agent any
    stages{
        stage('clone'){
            steps{
                sh 'echo "clone"'
                sh 'uname -r'
                sh 'nproc'
                sh 'df -h'
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
}
