pipeline {
    agent any
    stages {
        stage('Hello World') {
            steps {
                git url: 'https://github.com/siva000484/practice.git', branch: 'main'
                bat 'python hello.py'
            }
        }
        stage('Hello Wipro') {
            steps {
                git url: 'https://github.com/siva000484/practice.git', branch: 'main'
                bat 'python hellowipro.py'
            }
        }
        stage('Hello Jenkins') {
            steps {
                git url: 'https://github.com/siva000484/practice.git', branch: 'main'
                bat 'python hellojenkins.py'
            }
        }
    }
}
