node('docker-slave-java') {
    checkout scm
    withAnt() {
        sh "ant"
    }
}
