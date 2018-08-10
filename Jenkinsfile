node('docker-slave-java') {
    sh "echo '<project name=\"test\" default=\"default\" basedir=\".\">\n<target name=\"default\"><echo message=\"Hello World!\"/>\n</target>\n</project>' > build.xml"
    withAnt() {
        sh "ant"
    }
}
