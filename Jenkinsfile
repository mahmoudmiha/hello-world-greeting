pipeline {
    agent none
    stages {
        stage('Back-end') {
            agent {
                docker { image 'agent_java' }
            }
            steps {
                sh 'echo "hello"'
            }
        }
        stage('Front-end') {
            agent {
                docker { image 'agent_tomcat' }
            }
            steps {
                sh 'echo "word!"'
            }
        }
    }
}
