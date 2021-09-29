pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/BALABHASKARARAO/pileine-tes.git'
                echo 'Hello World'
                sh 'ls'
                sh 'cat bala.txt'
            }
        }
    }
}
