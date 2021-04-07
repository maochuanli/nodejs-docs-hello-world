node('linux') {
    stage('checkout') {
        // checkout code from repo
        checkout scm
        // build project, but skip running tests
        sh 'ls -la'
    }

    stage('build - test'){
	sh 'ls -la'
    }
}
