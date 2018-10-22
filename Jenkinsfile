pipeline {
    agent any
     stages {
      stage('Build'){
      steps {
       echo 'Running build automation'
       sh './gradlew build --no-deomon'
       archiveArtifacts artifacts 'dist/trainSchedule.zip'
       }
      }
     }
    }
