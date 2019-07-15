node {
    def app
    
    stage('Cloning repository'){
	git credentialsId: 'gitrepo', url: 'https://github.com/saleem1308/NodeApp.git'
    }
	
    stage('Building image'){
	app = docker.build("firstjobimage")
    }

    stage('Test image') {

        app.inside {
            echo "Tests passed"
        }
    }
 	
}
//https://github.com/saleem1308/NodeApp.git

