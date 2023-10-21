pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 5, unit: 'SECONDS')
    }
    stages{
        stage('Run Groovy Script') {
            steps {
                sh '''
                def j = 1
                while (j <= 5) {
                    echo "iteration number $j"
                    j++
                }
                '''
            }
        }
    }
}