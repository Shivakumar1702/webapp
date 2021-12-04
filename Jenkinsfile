pipeline{
    agent any
    stages{
        stage("build"){
            when{
                changelog "Create dummy"
            }
            steps{
                echo "Building the master branch"
            }
        }
    }
}
