pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo 'INICIO'
        bat 'Empezando pipeline'
      }
    }

    stage('Sistema') {
      steps {
        echo 'Sistema'
        bat '%DATE% %TIME%'
      }
    }

    stage('Aprobacion') {
      steps {
        input(message: '¿Continuar a FIN?', ok: 'Continuar')
      }
    }

    stage('Fin') {
      steps {
        echo 'FIN'
        bat 'empezando'
        bat 'fecha y hora: %DATE% %TIME%'
        bat 'terminado'
      }
    }

  }
}