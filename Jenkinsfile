pipeline {
   agent {
    node {
        label 'agent1'
    }
    }
    options {
        timeout(time: 1, unit: 'HOURS') 
        disableConcurrentBuilds()
    }
    environment {
        GREETING ='HELLO JENIKINS'
    }
    // parameters {
    //     string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')

    //     text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')

    //     booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')

    //     choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')

    //     password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
    
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
        // stage('Example') {
        //     steps {
        //         echo "Hello ${params.PERSON}"

        //         echo "Biography: ${params.BIOGRAPHY}"

        //         echo "Toggle: ${params.TOGGLE}"

        //         echo "Choice: ${params.CHOICE}"

        //         echo "Password: ${params.PASSWORD}"
        //     }
        // }
    }
     post { 
        always { 
            echo 'I will always say Hello again!'
             echo 'I will always say Hello again!'
        }
     }
        
    
}