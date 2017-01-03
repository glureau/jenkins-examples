node() {
	properties([
		parameters([
			booleanParam(defaultValue: false, description: 'set true if you are a god', name: 'imgod')
		]),
		
		// Without that, you could have a checkout during the build of the previous commit code, just crashing both builds!
		disableConcurrentBuilds()
	])
	
	stage ('DoSomething') {
		sh 'echo $imgod'
	}
}
