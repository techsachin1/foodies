pipeline {
    agent any 
    triggers {
        cron('* * * * *')
    }
    stages {
        stage ('code checkout') {
            steps {
                echo "code pull from repo"
            }
        }
        stage ('build1') {
            steps {
                echo "build project"
            }
        }



    }



}