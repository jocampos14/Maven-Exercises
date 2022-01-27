pipeline {
  agent any
  stages {
    stage('Mensaje') {
      steps {
        echo 'Iniciando Compilacion'
        sh 'mvn clean install'
        echo 'Compilacion Finalizada'
      }
    }

  }
}