pipleline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo "Running Jenkins Automation"
        sh "./gradlew build --no-daemon"
        archiveArtifacts artifacts: "dist/tranSchedule.zip"
      }
    }
  }
}
