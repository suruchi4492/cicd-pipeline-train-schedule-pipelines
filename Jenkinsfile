pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build ---daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip
      }
    }
  }
}
