pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    }
    parameters {
        string(name: 'count', description: 'count of iteration', defaultValue: 'integer')
    }
    stages{
        stage('Run Groovy Script') {
            steps {
                script {
                    integer j = 1
                    while (j <= 5) {
                        echo "iteration number $j"
                        j++
                    }
                }
            }
        }
    }
}