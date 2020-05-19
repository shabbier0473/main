pipeline{
    agent none
    tools {
        maven "MAVEN_HOME"
    }
    stages{
        stage("dev"){
            steps {
                sh "mvn compile"
            }
        }
    }
    
}
