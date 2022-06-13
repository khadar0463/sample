pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                sh 'Checkout scm'
            }
        }
        stage('Build') {
            steps {
                sh 'var/lib/jenkins/workspace/Declarative/cpp-tutorial/stage1/main; bazel build ...'
            }
        }
        
    }
}
