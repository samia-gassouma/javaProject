pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
 		echo 'Building the project..'
                sh 'mvn clean package -Dmaven.test.failure.ignore=true'
                
            }
        }
    }
}
