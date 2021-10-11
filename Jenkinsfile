pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                build quietPeriod: 1, job: 'BuildJob'
            }
        } 
    }
}
