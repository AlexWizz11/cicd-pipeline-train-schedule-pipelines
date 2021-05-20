pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo "Running build Information"
        sh './gradlew build --no-daemon'
        archiveAftifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
   }
 }
