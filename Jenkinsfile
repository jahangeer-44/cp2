pipeline{
    agent any
    stages{
        stage("test"){
            steps{
                script{
                    bat 'docker build -t my-node .'
                }
            }
        }
        stage("running"){
            steps{
                script{
                    echo 'Running '
                }
            }
        }
        stage("deploy"){
            steps{
                script{
                    echo 'deploy '
                }
            }
        }
    }
}