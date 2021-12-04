pipeline{
    agent any
    stages{
        stage("build"){
            when{
                changelog "Update dummy"
            }
            steps{
                echo "Building the master branch "
            }
        }
    }
}
