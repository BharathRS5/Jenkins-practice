pipeline {
    agent{
        node {
            label 'Agent-1'
        }  
    }

     stages {
        stage('Build') {
            steps {
                echo 'Building..'
              sh '''
                pwd
                ls -ltr
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

