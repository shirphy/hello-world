pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        echo 'test1'
      }
    }

    stage('test2') {
      steps {
        sleep 4
      }
    }

    stage('test3') {
      steps {
        writeFile(file: 'result.txt', text: 'test3 result', encoding: 'utf8')
      }
    }

  }
}