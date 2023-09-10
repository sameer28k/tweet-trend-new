pipeline {
    agent {
        node {
            label "maven"
        }
    }
environment {
    PATH = "/opt/apche-maven-3.9.4/bin:$PATH"
}
    stages {
       stage("build") {
        steps {
            sh 'mvn clean deploy' 
        }
       }

    }
}
