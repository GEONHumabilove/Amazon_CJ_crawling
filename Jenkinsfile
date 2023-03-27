pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('crawling') {
      steps {
        sh 'python Final_CJ_Amazon_crawling.py'
      }
    }
  }
}
