pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
	       sh 'git clone https://github.com/mranaligoswami/linuz.git'
	       sh 'docker build -t mranalidocker12345/img -f Dockerfile .'
               sh 'docker push mranalidocker12345/img'

            }
        }
    }
}
