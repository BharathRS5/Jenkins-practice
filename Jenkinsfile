pipeline {
    agent any

     stages {
        stage('Build') {
            steps {
                echo 'Building..'
              sh '''
                ls -ltr
                pwd
              '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
     }
}

