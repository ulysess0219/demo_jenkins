pipeline{
    agent {label 'master'}
    stages{
        stage('hello'){
            steps{
                sh 'echo hello'
                sh 'pwd'
            }
        }
        stage('bye'){
            steps{
                sh 'echo helloworld'
            }
        }
        stage('new'){
            steps{
                sh 'echo new'
            }
        }
    }
}
