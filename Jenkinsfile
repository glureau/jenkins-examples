node() {
	properties([
		disableConcurrentBuilds()
	])

	stage ('DoSomething') {
		timeout(time:1, unit:'MINUTES') {
			input message: 'Do you want to do something?'
		}
		sh 'pwd'
	}
}
