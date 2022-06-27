pipeline {
    agent { 
        docker { 
            image 'maven:latest' 
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('test') {
            steps {
                echo 'testing;
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}
