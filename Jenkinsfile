pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/ravdy/hello-world.git'
            }
        }
        stage('build') {
            steps {
                shell "mvn clean install"
            }
        }
    }
}
