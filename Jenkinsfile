pipeline {
    agent any
    options {
        ansiColor('xterm')
    }

    stages {
        stage('Hello Again') {
            steps {
                echo 'Hello World, again!'
            }
        }
        
        stage('Paint') {
            steps {
                echo '\033[34mHello\033[0m \033[33mcolorful\033[0m \033[35mworld!\033[0m'
            }
        }
    }
}
