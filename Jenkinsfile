pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                retry(3) {
                    sh 'ls -tal'
                }

                timeout(time: 3, unit: 'MINUTES') {
                    sh 'ls'
                }
            }
        }
    }
}
