pipeline {
    agent any
    options {
        disableConcurrentBuilds()
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