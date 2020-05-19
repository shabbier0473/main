pipeline{
    agent any
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
