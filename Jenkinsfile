// Allocate Build Node
node('master') {
    stage("Fetch Source Code") {
        git 'https://github.com/TrainingByPackt/Beginning-Continuous-Delivery-With-Jenkins'
    }
    stage("Testing") {
        sh 'echo testing is running'
    }
}
def printMessage(message) {
    echo "${message}"
}
