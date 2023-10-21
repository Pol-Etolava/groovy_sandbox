pipeline {
    agent any
    options {
        disableConcurrentBuilds()
    }
    parameters {
        text(name: 'text')
    }
    stages{
        stage('Run Groovy Script') {
            steps {
                script {
                    println{params.text}
                }
            }
        }
    }
}