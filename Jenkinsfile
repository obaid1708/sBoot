pipeline {
agent any
tools {
          jdk 'java8'   // or java8, based on what you installed on Jenkins
        // maven 'maven3
        }
stages {
  stage('compile'){
    steps {
  sh 'mvn compile'
  }
  }
  stage('test')
  { steps {
  sh 'mvn test'
  }
  }
  stage('build'){
    steps {
  sh 'mvn clean install'
}
  }
}
}
