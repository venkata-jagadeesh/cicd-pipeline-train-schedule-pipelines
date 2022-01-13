pipeline {
  agent any 
   stages {
     stage ('Build') {
       steps {
         echo 'Running build automation'
         sh './gradlew --no-deamon'
         archiveArtifacts artifacts: 'dist/trainschedule.zip'
       }
     }
  }
}
