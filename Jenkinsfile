pipeline{
    agent   { label 'mavenagent' }
    environment{
        PATH = "/opt/apache-maven-3.9.2/bin:$PATH"
    }
    stages{

        stage('builds'){
            steps{
                sh 'mvn clean deploy'
            }
        }
        
       
    }

}
