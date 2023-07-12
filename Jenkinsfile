
pipeline {
    agent any
    stages {
        stage("Build tag") {
            when {
                buildingTag()
            }
            steps {
                echo "hi bye tag"
            }
        }
    }
}
