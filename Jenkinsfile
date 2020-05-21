// Allocate Build Node
node('master') {
    stage("Fetch Source Code") {
        git 'https://github.com/attiqbhai/scratch-system-api'
    }
    stage("Testing") {
        sh 'echo testing is running'
    }
}
def printMessage(message) {
    echo "${message}"
}
