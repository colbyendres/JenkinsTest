pipeline {
   agent {
        label ‘main-host’
   }    
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'pip install -r requirements.txt'
            }
        }
    }
}
