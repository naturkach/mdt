pipeline {
    agent {
        docker {
            label 'Demo'
            image 'busybox'
        }
    }
    stages {
        stage('Stage') {
            steps {
                sh 'uname -a; ls -laR'
            }
        }
    }
}
