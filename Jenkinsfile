/* Jenkinsfile (Declarative Pipeline) */
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                cmd.exe /c echo "Hello Shell from CMD"
                echo 'Hello Shell'
                sh 'cd'
                sh 'mvn --version'
            }
        }
    }
}
