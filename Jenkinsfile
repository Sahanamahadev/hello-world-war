pipeline {
    agent { label 'java4' } 
    stages {
        stage('checkout') {
            steps {
                sh 'git clone https://github.com/Sahanamahadev/hello-world-war.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
      
}
}
