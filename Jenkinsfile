pipeline {
    agent any

    
    stages {
        
        stage("build") {
            steps {
                echo "Building.."
                sh "ls $workspace/"
                sh "mvn clean install;"
            }
        }
        
        stage("test") {
            steps {
                echo "Testing.."
            }
        }
        
        stage("deploy") {
            steps {
                echo "Deploying.."
            }
        }
        
    }
}
