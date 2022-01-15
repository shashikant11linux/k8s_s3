pipeline {
    agent any

    
    environment {
        workspace_path = '/home/ec2-user/jenkins-data/jeknins_home/workspace'
        JNK_PATH = "${env.WORKSPACE}"
    }
    
    stages {
        stage('Build') {
            steps {
               
                sh './test.sh'
            }
        }
    }
}
