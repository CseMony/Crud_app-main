pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                git 'https://github.com/CseMony/Crud_App.git' 
            }
        }
        stage('Test'){
            steps {
                echo 'Testing the application' 
            }
        }
        stage('Deploy') {
            steps {
                 echo 'Deploying the application' 
            }
        }
    }
}