pipeline {
    agent any

    
    environment {
        workspace_path = '/home/ec2-user/jenkins-data/jeknins_home/workspace/$JOB_NAME'
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'echo workspace  = $workspace_location/$JOB_NAME'
                sh '''
                   ./jenkins/build/test.sh"
                '''
            }
        }
    }
}
