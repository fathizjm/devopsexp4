pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        bat 'php -version'
      }
    }
    stage('copy php code on xampp server') {
      steps {
        bat 'xcopy /s "*" "C:/xampp/htdocs/DevOps" /Y'

      }
    }
      
  }     
  }
