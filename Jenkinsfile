pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                build quietPeriod: 1, job: 'BuildJob'
            }
        }
        stage('Build') {
            steps {
                build quietPeriod: 1, job: 'First_Job'
            }
        }
      
    }
}
