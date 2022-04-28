pipeline {
    agent any
    stages {
        stage('Path') {
            steps {
                sh 'pwd'
                sh 'cd /root/Desktop'
                sh 'pwd'
            }
	}
        stage('File') {
            steps {
                sh 'pwd'
                sh 'touch /root/Desktop/fromgithub'
                sh 'pwd'
            }
	}
    }
}
