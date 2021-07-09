node {
 	// Clean workspace before doing anything
    deleteDir()

    try {
        stage ('Clone') {
        	echo "cloning"
        }
        stage ('Build') {
        	sh "echo 'shell scripts to build project...'"
        }
    
      	stage ('Deploy') {
            sh "echo 'shell scripts to deploy to server...eeeeeeeeeeeeeeeee'"
      	}
    } catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}

