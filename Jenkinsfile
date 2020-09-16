pipeline{
    agent any
    
    environment{
        PATH = "/opt/maven3/bin:$PATH"
    stages{
        stage("Git Checkout"){
            steps{
                echo"build is success"
                
                stage("Maven build"){
            steps{
                sh "mvn clean package"
                sh "mv target/*.war target/myweb.war"
                
            }
        }
        
    }

}
