pipeline {
    agent any
  stages {
    stage('Git Clone') {
        steps {
            git 'https://github.com/rahulmittal123/spring3hibernate.git'
        }
    }
    stage('Maven Clean') {
        steps {
            sh 'mvn clean'
        }
    }
    stage('Maven Package') {
        steps {
            sh 'mvn package'
        }
    }
  }
}
