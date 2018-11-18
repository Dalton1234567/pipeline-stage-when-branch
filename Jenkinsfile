pipeline{
    agent any
    stages{
        stage('master  build'){
            when{
                branch 'master'
            }
            steps{
                echo 'building branch'
            }
        }
        stage('dev build'){
            when{
                branch 'dev'
            }
            steps{
                echo 'building dev'
            }
        }
    }
}
