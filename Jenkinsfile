/* Jenkinsfile (Declarative Pipeline) */
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo 'Hello Shell 0'
                /*cmd.exe '/c echo "Hello Shell from CMD"'*/
                /*echo 'Hello Shell 1'*/
                /*sh 'cmd.exe /c echo "Hello Shell from CMD"'*/
                /*echo 'Hello Shell 2'*/
                /*sh 'cd'*/
                /*sh 'mvn --version'*/
                /* ************************
                possibly solution 09.11.2018 #20181109 - 
                In the next section of the Jenkins.io doc running multiple steps 
                is a hint to Shell commands under Windows. Instead of sh use bat.
                ************************* */
            }
        }
    }
}
