pipeline {
    agent any
    tools {
  maven 'M2_HOME'
    }
    stages{
        stage('build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }

}