pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                 checkout scm
            }
        }
        stage('Bazel build') {
            steps {
                sh "var/lib/jenkins/workspace/Declarative/cpp-tutorial/stage1/main; bazel build hello-world.cc"
            }
        }
        
    }
}
