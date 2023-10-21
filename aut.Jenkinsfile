pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    }
    stages{
        stage('Run Groovy Script') {
            steps {
                script {
                    def j = 1
                    while (j <= 5) {
                        echo "iteration number $j"
                        j++
                    }
                }
            }
        }
    }
}