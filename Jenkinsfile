pipeline {
    agent any
    
    stages {
        
        stage("build") {
            steps {
                echo "Building.."
                sh "mvn -p $workspace/maven-quick-start/pom.xml clean install;"
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
