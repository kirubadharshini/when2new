
pipeline {
    agent any
    stages {
        stage("Build") {
            when {
                branch 'main'
            }
            step {
                echo "print master"
            }
        stage("Build Dev")
            when {
                branch 'dev'
            }
            step {
                echo " print dev"
            }
        
            
        }
    }
}
