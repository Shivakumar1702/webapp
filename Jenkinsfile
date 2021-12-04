pipeline{
    agent any
    stages{
        stage("build"){
            when{
                tag "1.0"
            }
            steps{
                echo "Building the master branch"
            }
        }
    }
}
