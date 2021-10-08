pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        // maven "MAVEN_HOME"
        echo "Loading Tools"
    }

    stages {
        stage('Build') {
            steps {
              echo "Build Steps"
            }

            post {
               echo "Build post"
                }
            }
        }

        stage('Get Smoke Tests') {
            steps{
                echo "Get Smoke Tests"
            }
        }
    }
    
}
