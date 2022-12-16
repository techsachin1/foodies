pipeline{
    agent any
    stages {
        stage('cloning project') {
            steps {
                echo "this stage is for git cloning"
            }
        }
        stage('Project execution') {
            steps {
                sh '''sudo apt update -y''' 
                echo "repo updated"
            }
        }
    }
}