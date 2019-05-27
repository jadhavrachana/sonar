pipeline {

    agent any

    stages {

        stage('SCM') {

            steps {
                    git "https://github.com/jadhavrachana/sonar.git"
                //
            }
        }

        stage('Test') {

            steps {
                    sh "mvn test"
                //
            }
        }

        stage('code analysis') {

            steps {
                    sh "/sonar_scanner/bin/sonar-scanner"
                //
            }
        }

        stage('Deploy1') {

            steps {
                   echo "this is step1"
                //
            }
       }

       stage('Deploy2') {

            steps {
                  echo "this is step1"
                //
            }

        }

    }
}
