@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('integrationArtifactUpdateConfiguration Command') {
		integrationArtifactUpdateConfiguration script: this
  }
}
