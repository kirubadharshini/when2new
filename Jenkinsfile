
pipeline {
    agent any
    stages {
        stage("Build master") {
            when {
                branch 'master'
            }
            steps {
                echo "print master"
            }
         }
        stage("Build Dev"){
            when {
                branch 'dev'
            }
            steps {
                echo " print dev"
            }
         }
    }
}
