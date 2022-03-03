pipeline {
    agent any{
        stages{
            stage ("Build the artifact"){
                steps {
                    script{
                        sh echo "building the artifact"
                    }
                }
            }
            stage ("testing the artifact"){
                steps{
                    script {
                        sh echo "tested successfully..ready for deployemnt"
                    }
                }
            }
            stage ("deploy the artifact"){
                steps {
                    script {
                        sh echo "deploying the artifact"
                    }
                }
            }
        }
    }
}