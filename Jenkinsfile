
pipeline {
    agent any
    stages {
        stage("Build") {
            when {
                buildingTag()
            }
            step {
                echo "hi bye tag"
            }
        }
    }
}
