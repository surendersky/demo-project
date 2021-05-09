pipeline {
    agent any 
    stages {
        stage('Example Test') {
         steps {
                echo 'Hello World'
                sh 'touch surender.html'
                sh 'rsync -avzh -e ssh  /var/lib/jenkins/workspace/demo-project/*.html root@172.31.24.129:/opt/index.html'
                }
        }
    }
}

