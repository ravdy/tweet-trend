pipeline{
    agent   any
    environment{
        PATH = "/opt/apache-maven-3.9.2"
    }
    stages{

        stage('build'){
            steps{
                sh 'mvn package'
            }
        }
        
       
    }

}
