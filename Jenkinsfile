pipeline{
    agent any
    stages{
        stage("build"){
            when{
                changelog "Update Jenkinsfile"
            }
            steps{
                echo "Building the master branch "
            }
        }
    }
}
