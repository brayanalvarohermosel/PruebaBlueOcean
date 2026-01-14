pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo 'INICIO'
        bat 'echo Empezando pipeline'
      }
    }

    stage('Sistema') {
      steps {
        echo 'Sistema'
        bat 'echo %DATE% %TIME%'
      }
    }

    

    stage('Fin') {
      steps {
        echo 'FIN'
        bat 'echo empezando'
        bat 'echo fecha y hora: %DATE% %TIME%'
        bat 'echo terminado'
      }
    }

  }
}
