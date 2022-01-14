pipeline {
    agent any

    
    environment {
        workspace_path = '/home/ec2-user/jenkins-data/jeknins_home/workspace/$JOB_NAME'
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'echo jinkinsfile job name = $JOB_NAME'
                sh '''
                   ./test.sh"
                '''
            }
        }
    }
}
