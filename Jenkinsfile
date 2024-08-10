pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('checkout') {
            steps {
                git branch: 'main','new', url: 'https://github.com/Fir3eye/springboot-demo.git'
            }
        }
        stage('pull') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
