pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh '/usr/bin/javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh '/usr/bin/javac Hello'
            }
        }
    }
}


