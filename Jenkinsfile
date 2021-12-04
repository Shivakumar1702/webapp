pipeline{
    agent any
    stages{
        stage("build"){
            when{
                tag "v1.0"
            }
            steps{
                echo "Building the master branch"
            }
        }
    }
}
