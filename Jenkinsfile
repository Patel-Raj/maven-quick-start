pipeline {
    agent any
    
    stages {
        
        stage("build") {
            steps {
                echo "Building.."
                sh "pwd;"
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
