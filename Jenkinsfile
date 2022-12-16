pipeline{
    agent any
    stages {
        stage('cloning project') {
            steps {
                echo "this stage is for git cloning"
            }
            steps {
                echo "this is second step in same stage"
            }
        }
        stage('Project execution') {
            steps {
                sudo apt update -y 
                echo "repo updated"
            }
        }
    }
}