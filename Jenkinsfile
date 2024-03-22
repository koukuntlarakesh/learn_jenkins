pipeline {
   agent {
    node {
        label 'agent1'
    }
    }

    stages {
        stage('Build') {
            steps {
                echo  'Building...'
                echo 'project'
            }
        }
        stage('Test') {
            steps {
                echo  'Testing...'
                echo 'UPDATE'
                echo  'LATEST'
            }
        }
        stage('Deploy') {
            steps {
                echo  'Deploying'
            }
        }
    }
     post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}