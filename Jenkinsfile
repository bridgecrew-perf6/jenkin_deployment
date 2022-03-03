pipeline{
    agent any
    stages{
        stage("building the artifact"){
            steps{
                script{
                    sh echo "build the artifact"
                }
            }
        }
        stage("testing the stages"){
            steps{
                script{
                    sh echo "testing the artifact"
                }
            }
        }
        stage("deploying tthe artifact"){
            steps{
                script{
                    sh echo "deployed successfully"
                }
            }
        }
    }
}