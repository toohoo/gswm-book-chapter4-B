/* Jenkinsfile (Declarative Pipeline) */
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo 'Hello Shell 0'
                cmd.exe '/c echo "Hello Shell from CMD"'
                echo 'Hello Shell 1'
                sh 'cmd.exe /c echo "Hello Shell from CMD"'
                echo 'Hello Shell 2'
                sh 'cd'
                sh 'mvn --version'
            }
        }
    }
}
