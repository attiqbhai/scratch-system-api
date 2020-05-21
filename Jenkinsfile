// Allocate Build Node
node('master') {
    stage("Fetch Source Code") {
        printMessage("Fetching")
        git 'https://github.com/attiqbhai/scratch-system-api'
    }
    stage("Testing") {
        printMessage("Testing")
        sh 'echo testing is running'
    }
}
def printMessage(message) {
    echo "${message}"
}
