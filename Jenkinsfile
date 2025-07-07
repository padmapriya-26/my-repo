pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "building step"
            }
        }
        stage('Groovy stage') {
            steps {
                script {
                    def course='ks8'
                    println("print the condition $(course) course")
                }
            }
        }
    }
}
