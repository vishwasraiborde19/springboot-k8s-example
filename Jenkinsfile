pipeline {
  agent none
  stages {
    stage('hello') {
      steps {
        echo 'hello'
      }
    }

    stage('check out') {
      steps {
        git 'https://github.com/vishwasraiborde19/platform-cloud.git'
      }
    }

    stage('') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

  }
}