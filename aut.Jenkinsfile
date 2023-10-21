pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 5, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
            sh 'def j = 1
                while (j <= 5) {
                    println("iteration number $j")
                    j++
                }'
            }
        }
    }
}