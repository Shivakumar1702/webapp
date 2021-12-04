pipeline{
    agent any
    stages{
        
        stage('build master'){
            when{
                branch 'master'
            }
            steps{
                echo 'building the master branch'
            }
        }
        
        stage('build test'){
            when{
                branch 'test'
            }
            steps{
                echo 'building the test branch'
            }
        }
    }
}
