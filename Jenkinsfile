node('nodejs){
	stage('Checkout'){
		git branch: 'main', url: 'https://github.com/fazrezalyusoff/do400-pipelines-control'
	}
	stage('Backend Tests'){
		sh 'node ./backend/tests.js'
	}
	stage('Fronted Tests'){
		sh 'node ./frontend/tests.js'
	}
}
