pipeline { 
    agent {
      label 'ubuntu'
    } 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                sh 'echo "Build Stage"' 
            }
        }
        stage('Test'){
            steps {
                sh 'echo "Test Stage"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploy stage"'
            }
        }
    }
}
