pipeline {
    agent { label 'Slaver-Agent' }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git 'https://github.com/lenamduytuan/genkinfiledemo.git'
            }
        }
    }
}
