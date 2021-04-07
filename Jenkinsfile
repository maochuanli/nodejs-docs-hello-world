node('linux') {
    stage('checkout') {
        checkout scm
        // build project, but skip running tests
        sh 'ls -la'
    }

    stage('build - test'){
	sh 'ls -la'
    }
}
