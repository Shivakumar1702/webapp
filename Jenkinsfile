pipeline{
    agent any
    stages{
        stage("build"){
            when{
                buildingTag "1.0"
            }
            steps{
                echo "Building the master branch"
            }
        }
    }
}
