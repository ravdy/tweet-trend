pipeline{
    agent   any
    environment{
         PATH = "/opt/apache-maven-3.9.1/bin:$PATH"
    }
    stages{

        stage('build'){
            steps{
                sh 'mvn package'
            }
        }
        
       
    }

}
