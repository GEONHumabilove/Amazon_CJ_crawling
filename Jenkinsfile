pipeline {
  agent any
  stages {
    stage('version') {
      sh 'python --version'
    }
    stage('crawling') {
      sh 'python Final_CJ_Amazon_crawling.py'
    }
  }
}
