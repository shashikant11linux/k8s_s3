pipeline {
    agent any

    
    environment {
        workspace_path = '/home/ec2-user/jenkins-data/jeknins_home/workspace/$JOB_NAME'
    }
    
    stages {
        stage('Build') {
            steps {
               
                sh '''
                   ./test.sh"
                '''
            }
        }
    }
}
