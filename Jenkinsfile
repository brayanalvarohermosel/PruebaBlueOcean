pipeline {
  agent any
  stages {
    stage('Inicio') {
      agent any
      steps {
        echo 'INICIO'
        bat 'echo Empezando pipeline'
      }
    }

    stage('Sistema') {
      agent any
      steps {
        echo 'Sistema'
        bat 'echo %DATE% %TIME%'
      }
    }

    stage('Fin') {
      agent any
      steps {
        echo 'FIN'
        bat 'echo empezando'
        bat 'echo fecha y hora: %DATE% %TIME%'
        bat 'echo terminado'
      }
    }

  }
}
