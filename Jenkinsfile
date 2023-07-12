
pipeline {
    agent any
    stages {
        stage("Build") {
            when {
                buildingTag()
            }
            steps {
                echo "hi bye tag"
            }
        }
    }
}
