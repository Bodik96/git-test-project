pipeline {
    agent {aws-devserv}

    stages {
        stage('Copy file on node to Apache directory') {
            steps {
                cp -r /home/jenkins/workspace/'Github job' /var/www/testprod
            }
        }
    }
}
