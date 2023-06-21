pipeline{
    agent   { label 'mavenagent' }
    environment{
        PATH = "/opt/apache-maven-3.9.2/bin"
    }
    stages{

        stage('build'){
            steps{
                sh 'mvn package'
            }
        }
        
       
    }

}
