node {
 	// Clean workspace before doing anything
    deleteDir()

    try {
        stage ('Clone') {
          sh "date"
        }
    } catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
