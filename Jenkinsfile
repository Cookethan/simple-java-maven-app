pipeline{
    agent any
    tools{
    docker 'default'
  }
    stages {
        stage('Build'){
            steps{
                sh 'mvn -v'
            }
    }
    }
}
