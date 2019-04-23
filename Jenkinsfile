pipeline {

    // Where to run stuff.
    agent {
        node {
            lable 'master_01'
        }
    
    }

    // What to run goes here.
    stages {
        stage('Stage_1') {
            steps {
                bat 'echo "Hello i am in stage one"' 
                bat 'mkdir C:\Progra~1\Java\new_file'
            }
        }
        stage('Stage_02'){
            steps {
                bat 'echo "Hello iam in stage 2"'
            }
        }
    }
}
