pipeline {	
    agent any	
    options {	
        checkoutToSubdirectory('someSubDir')	
    }	
    stages {	
        stage('Build') {	
            steps {	
                sleep(time: 10, unit: 'SECONDS') 	
                echo 'Hello World'	
            }	
        }	
    }	
}	
