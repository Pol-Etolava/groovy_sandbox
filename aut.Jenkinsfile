pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    }
    parameters {
        text(name: 'count', description: 'Count of iteration', defaultValue: '10')
    }
    stages{
        stage('Run Groovy Script') {
            steps {
                script {
                    if (!count.isInteger()) {
                    count = 10
                    }
                    integer j = 1
                    while (j <= count) {
                        echo "iteration number $j"
                        j++
                    }
                }
            }
        }
    }
}