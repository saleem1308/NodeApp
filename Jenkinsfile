node {
    def app
    
    stage('Cloning repository'){
	git credentialsId: 'gitrepo', url: 'https://github.com/saleem1308/NodeApp.git'
    }
	
    stage('Building image'){
	app = docker.build("firstjobimage")
    }
	
	/*stage('Push image'){
		docker.withRegistry('<<your-docker-registry>>', '<<your-docker-registry-credentials-id>>') {
   	 }*/
        
}
//https://github.com/saleem1308/NodeApp.git

