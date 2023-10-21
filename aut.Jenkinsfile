pipeline {
    agent any
    options {
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