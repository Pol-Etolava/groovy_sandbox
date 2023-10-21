pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    }
    parameters {
        integer(name: 'count', description: 'count of iteration')
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