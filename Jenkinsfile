pipeline {
  agent any
  stages {
    stage('Mensaje') {
      steps {
        echo 'Iniciando Compilacion'
      }
    }

    stage('Cambio de rama') {
      parallel {
        stage('Cambio de rama') {
          steps {
            sh 'git switch answer4'
          }
        }

        stage('texto') {
          steps {
            echo 'Cambiando de rama'
          }
        }

      }
    }

    stage('Compilacion') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}