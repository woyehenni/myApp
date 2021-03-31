pipeline {
  agent any
  stages {
    stage('Say Hello') {
      environment {
        NAME = 'FaSheng Gu'
      }
      steps {
        sh 'echo "Helllo $NAME, Current date and time: $(date)"'
      }
    }

  }
}